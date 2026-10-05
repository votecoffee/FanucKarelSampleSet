# 693 source-diagnostic controls

Start with [the report](../../../Evidence/Diagnostic693_2026-09-30/REPORT.md). This folder contains `DG0001.KL` through `DG0020.KL`, each with a corresponding native V8.33 PC under `PC/V8.33/Diagnostic693`. The first seven also have an RS sidecar under `RS/V8.33/Diagnostic693` and were compiled twice, with and without `/r`.

The [results ledger](../../../Evidence/Diagnostic693_2026-09-30/RESULTS.json) ties every source and compiled artifact to a SHA-256 digest, native record scan, WIP972 replay counts, and original 693-diagnostic ledger hash. Compiler logs and replayed candidate text are in the evidence directory. The sources are controlled examples of declaration ownership, unsafe source expressions, and unresolved native spans; they are not recovered source for the twelve original PCs.

For reproduction, run `py -3 -X utf8 build_diagnostic693_controls.py` from the evidence directory. The script compiles in isolated scratch directories using `ktrans.exe /ver V8.33-1`, uses `/r` only for the first seven controls, and leaves the original PCs and decoder read only.
