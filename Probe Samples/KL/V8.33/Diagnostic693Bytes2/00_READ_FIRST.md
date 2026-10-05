# Routine-boundary byte controls

Start with [the report](../../../Evidence/Diagnostic693Bytes2_2026-09-30/REPORT.md). The 31 `BZ*.KL` files all compiled to native V8.33 PCs under `PC/V8.33/Diagnostic693Bytes2`. [RESULTS.json](../../../Evidence/Diagnostic693Bytes2_2026-09-30/RESULTS.json) pins source, log, PC, compiler, and original-diagnostic hashes plus every complete raw-record match.

These sources vary the number of routine formals, the next routine's compact or typed locals, and ABORT placement inside SELECT. They investigate native bytes at routine boundaries and control-flow edges. A matching boundary descriptor does not reveal original declaration names or prove that the entire routine is recovered.

The [combined corpus scan](../../../Evidence/Diagnostic693Bytes_2026-09-30/EXISTING_CORPUS_EXACT_RAW.json) verifies all 698 V8.33 probe PCs and indexes complete raw-record matches against all 352 unresolved original-PC spans. Rebuild this set with `py -3 -X utf8 build_diagnostic693_byte_followup.py` from the evidence directory; the script compiles in isolated scratch directories.
