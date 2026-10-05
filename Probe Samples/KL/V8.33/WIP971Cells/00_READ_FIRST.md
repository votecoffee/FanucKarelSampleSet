# WIP971 2C cell probes — read this first

These 50 V8.33 KL cases interrogate the **80 physical, source-type-unproved 2C cells** in the maintained PC Decompiler 4 WIP971 direct reports. The [evidence report](../../../Evidence/WIP971Cells_2026-09-30/REPORT.md) explains what the compiler runs established and where the type inference remains blocked.

Use [PROBE_INDEX.csv](PROBE_INDEX.csv) to pick a source. Its `WCnnnn.KL` has a matching native KTRANS output at `PC/V8.33/WIP971Cells/wcnnnn.pc` when `source_compile_success` is true. `WC0032.KL` is an intentional compiler-rejected negative control; its error is retained under `Evidence/WIP971Cells_2026-09-30/compiler_logs/`.

For original-PC work, start with [TARGET_80_CELLS.csv](../../../Evidence/WIP971Cells_2026-09-30/TARGET_80_CELLS.csv), then inspect [TARGET_186_REFERENCE_WINDOWS.json](../../../Evidence/WIP971Cells_2026-09-30/TARGET_186_REFERENCE_WINDOWS.json) for raw direct-reference records. [REFERENCE_MOTIF_TRIAGE.csv](../../../Evidence/WIP971Cells_2026-09-30/REFERENCE_MOTIF_TRIAGE.csv) links simple three-opcode neighborhoods to controlled probes. A motif match is only a place to investigate; its `source_type_proved` field is deliberately false for every row. The [manifest](../../../Evidence/WIP971Cells_2026-09-30/manifest.json) has compiler and file hashes, native 2B/2C records, and probe reference sites.

The 80 cells are physical storage units, not a count of original KL declarations. A three-cell VECTOR and three scalar locals can have the same compact 2C extent. Do not turn any probe match into an original declaration without independent same-PC owner, writer, consumer, formal/return, and rejecting-alternative evidence.
