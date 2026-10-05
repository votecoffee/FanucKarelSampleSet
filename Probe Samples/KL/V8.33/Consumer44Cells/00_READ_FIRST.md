# Consumer 44-cell compiler controls

Start with the [report](../../../Evidence/Consumer44Cells_2026-09-30/REPORT.md). The [index](PROBE_INDEX.csv) identifies 40 controlled KL sources: scalar INTEGER/BOOLEAN/REAL store-and-read alternatives, compact-frame offset sweeps, 141/143 literal stores, and `PBCORE::READ_KB` output-address permutations. The paired native PCs are in `../../../PC/V8.33/Consumer44Cells/`.

All sources were compiled with `ktrans.exe /ver V8.33-1` in separate scratch directories without `robot.ini`. The evidence directory contains compiler logs, source/PC hashes, all 184 original-site records checked against the four pinned PCs, and a one-row-per-cell comparison CSV. Raw-record matching here is bounded to each store pair, read/compare triple, or address record. It is not a whole-routine or whole-PC comparison.
