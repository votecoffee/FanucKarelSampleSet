# KL sources that generate RS sidecars

Read the [results report](../../../Evidence/RSCells_2026-09-30/REPORT.md), then [PROBE_INDEX.csv](PROBE_INDEX.csv) and the selected case directory. Each `RSnnnn/RSCELL.KL` is a complete V8.33 KAREL program. The shared program name keeps cross-source PC-byte comparisons meaningful; the case directories keep outputs separate.

Compile from a clean scratch directory containing the chosen `RSCELL.KL`:

```powershell
& 'C:\Program Files (x86)\FANUC\WinOLPC\bin\ktrans.exe' /r /ver V8.33-1 RSCELL.KL
```

KTRANS creates `rscell.pc` and `rscell.rs`. The retained outputs are under `PC/V8.33/RSCells/<case>/` and `RS/V8.33/RSCells/<case>/`. The [manifest](../../../Evidence/RSCells_2026-09-30/manifest.json) pins both files and the compiler logs. The [reproduction script](../../../Evidence/RSCells_2026-09-30/scripts/build_rs_cell_probes.py) also compiles each source without `/r` in a separate scratch directory and verifies that the PC bytes are unchanged.

Cases `RS0001`–`0007` isolate erased scalar type, VECTOR-versus-three-scalars partition, and compact-pool order. `RS0008`–`0011` add typed `2B` descriptors and declaration interleaving. Later cases cover used cells, aliases, a custom structure, a formal, and multiple routines. RS rows reveal the declarations of these compiler-produced controls; they do not identify a historical PC's unknown cells without its authenticated, paired RS.
