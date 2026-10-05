# RSCELL maximal KL uncertainty report

Original PC SHA-256: `e178c4126e38c9f31c7d1d17e87315eac66612fa6d090d7bbd0d8a34e899c620`  
KL SHA-256: `80b062732ef8d2129ad52733e9d25a628e953837427077d596bbb0b00e29cdb4`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 28
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 2 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- WIP compact type choices: {'REAL': 2}

## Unproved rendering methods used

- None.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
