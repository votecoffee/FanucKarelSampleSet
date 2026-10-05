# V8.33 untyped 2B/2C prolog-pair probes

This is a **107-source / 107-PC controlled compiler corpus** for local-frame typing holdouts. Each `B2Cnnnn.KL` under `KL/V8.33/Probes/` was compiled by native KTRANS V8.33 Build 25 to the same-numbered lowercase `.pc` under `PC/V8.33/Probes/`. Every output was decompressed and statically scanned; each contains an adjacent native `2B` typed-descriptor record followed by a `2C` compact-cell record. No probe was accepted on compiler exit code or source declarations alone.

Use `PROBE_INDEX.csv` to find cases by family and source intent. `PROBE_MANIFEST.json` records each source/PC SHA-256, compiler log, code length, direct mode-FF local load/store counts, and the **raw hex and code-relative offsets** of every observed `2B/2C` pair. `PC/V8.33/Probes/Logs/` holds the native compiler output. `BUILD_CONFIG.ini` is the exact version/path/support configuration used for the build; the compiler was run from a separate scratch directory, so the installed FANUC tree and this source directory were not compiler output locations.

| Family | Cases | What the pair isolates |
| --- | ---: | --- |
| `unused_type`, `unused_count` | 17 | Unreferenced locals, compact-cell counts, and declaration-only evidence |
| `order`, `prefix_array`, `prefix_struct` | 19 | Declaration order and array/structure 2B prefixes before 2C cells |
| `literal_store`, `small_compare` | 18 | Literal-only writers and BOOLEAN/INTEGER zero/one equality ambiguity |
| `literal_relation`, `formal_relation` | 24 | All six INTEGER/REAL comparisons against literals and typed formals |
| `formal_copy`, `array_load`, `formal_member` | 10 | Typed formal, array, and aggregate-member producers |
| `native_convert`, `arithmetic`, `for_index` | 7 | ROUND/TRUNC, scalar operators, and FOR indices |
| `return_cell`, `dual_return` | 6 | One- and two-path typed local returns |
| `multi_writer`, `branch_writer` | 6 | Multiple writers to a single compact cell |

The 107 observed pairs have 2C counts of one cell in 97 probes, two cells in four, three cells in two, four cells in three, and eight cells in one. Twenty-six probes contain no direct mode-FF `21` load or `23` store; this is a narrow record-count observation, not proof that the program has no other variable access. `B2C0032`/`B2C0033` are literal-only scalars after structure prefixes, patterned on the kind of unresolved `LOCAL_MIX` declaration in the earlier SP95DECL control. `B2C0100`–`B2C0104` cover typed formal members and aliases of the kind tested by SP91BIND. `B2C0047`–`B2C0054` explicitly contrast INTEGER and BOOLEAN small-literal equality/inequality.

Some declaration-only types (`STRING`, `XYZWPR`, `XYZWPREXT`, `POSITION`, `JOINTPOS6`) occupy the typed 2B descriptor rather than providing a compact 2C cell by themselves. Those probes include an unused INTEGER sentinel to retain the pair and expose the placement difference. `BYTE` and `SHORT` are used as structure fields, since bare local declarations of those types were rejected by this compiler. Read the source declaration and the raw pair together; do not treat every declared local as a 2C cell.

These are synthetic source/compiler pairs. They establish what **these exact sources** produce under V8.33 Build 25. They do not identify the original names or types of unresolved library cells merely because a target shares a literal opcode. In particular, `9C`/`9D` literal and small equality patterns can occur with multiple source types, and an unreferenced cell has no use-site type evidence. A target inference still requires unique routine/cell ownership, matching producer/consumer records, writer agreement, and independently justified type constraints.

To reproduce one build on this PC, copy its KL and `BUILD_CONFIG.ini` into a clean scratch directory, name the copied config `robot.ini`, and run `C:\Program Files (x86)\FANUC\WinOLPC\bin\ktrans.exe B2C0001.KL` from that directory. Compare the resulting `.pc` SHA-256 with `PROBE_INDEX.csv`. Do not execute these probes on a controller; they were compiled only.
