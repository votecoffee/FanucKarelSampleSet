# Consumer 79-cell trace probes

Read the [report](../../../Evidence/Consumer79Trace_2026-09-30/REPORT.md) first. `C790001.KL`–`C790017.KL` cover `TRIGCAM` read-before-explicit-store paths, the `FOVSTACAL` indexed-array builder, and unused one- and three-cell compact pools. Their native V8.33 PCs are under `../../../PC/V8.33/Consumer79Trace/`. The evidence directory contains pinned input hashes, compiler logs, six `/r` RS sidecars, full PC comparisons, and exact-record comparisons with the original PCs.

Each source was compiled in its own scratch directory with `ktrans.exe /ver V8.33-1`; the six unused-pool controls also used `/r`. The two groups of unused-pool sources intentionally share a `PROGRAM` name and pad declaration lines to equal physical length. This makes whole-PC byte comparisons meaningful. No control supplies an original RS sidecar or a source form for native `1A 13`.
