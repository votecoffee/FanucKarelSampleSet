# Third-party language feature probes

Start with the [report](../../../Evidence/ThirdPartyFeatures_2026-09-30/REPORT.md) and [index](PROBE_INDEX.csv). **18 newly written KL controls** compile with native KTRANS V8.33 Build 25; their matching PCs are under [`PC/V8.33/ThirdPartyFeatures`](../../../PC/V8.33/ThirdPartyFeatures/). The evidence folder has compiler logs, guarded decompiler candidates, candidate compile logs, record-alignment metrics, and hashes.

The controls isolate `FOR ... DOWNTO`, `REPEAT`/`UNTIL`, `DELAY`, arithmetic and bitwise expressions, STRING helpers, `UNINIT`, `ARRAY_LEN`, `GET_VAR`/`SET_VAR`, register/position APIs, semaphores, FILE reads, TPE parameters, TP output, nested `SELECT`, simple and dotted `%INCLUDE`, `CONDITION`/`WHEN`, and `GOTO`. The `observed_in` column names third-party or FANUC examples that suggested the probe; each probe is a new controlled source, not a copy of an upstream program. They were compiled and decompiled but never executed on a controller.

Archive `.klt`, `.klh`, `.klc`, and `.ftx` findings and future probe leads are documented in [Archive support findings](../../../../3rd%20Party%20Samples/ARCHIVE_SUPPORT_FINDINGS.md).
