# WIP972 frontier follow-up probes

Read [the report](../../../Evidence/WIP972Frontier2_2026-09-30/REPORT.md) first. `FY0001.KL` through `FY0047.KL` are controlled V8.33 KAREL sources. Matching native PCs are under `PC/V8.33/WIP972Frontier2/` relative to the Probe Samples root. The evidence folder holds a SHA-256 manifest, compiler logs, and exact opcode-window matches.

Each source changes a branch, call, array/formal access, string operation, or value-store pattern. All were built with `ktrans.exe /ver V8.33-1` in isolated scratch directories without `robot.ini`. The controls establish opcode motifs only. Do not infer the source type, declaration count, or recovered source of any original PC cell from a five-opcode overlap.

To reproduce, run `py -3 -X utf8 build_wip972_frontier2.py` from the archived script in the evidence folder or from the working copy. This regenerates the KL/PC/log and manifest files in their current locations.
