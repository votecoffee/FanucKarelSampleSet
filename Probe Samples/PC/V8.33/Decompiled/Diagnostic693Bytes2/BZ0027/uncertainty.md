# BZ0027 maximal KL uncertainty report

Original PC SHA-256: `9f237f952a70d33e7a1ee9a3fbc21b72d3b2f4fe802236acc6eb499372e2b08c`  
KL SHA-256: `3c624b2f5f96f640480ec43c7b5ac8531681bfd772984e330401a6bcb0c63113`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 3
- Additional unproved statements emitted as code: 1 (25.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 19
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 1 (1 directly referenced)
- Exact direct sites to unknown cells: 1
- WIP compact type choices: {'BOOLEAN': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
