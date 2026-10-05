# DGCASE maximal KL uncertainty report

Original PC SHA-256: `655053c52c95dccf658eb144ec53ed94331fed9c89f3a2d9282d628988abcec2`  
KL SHA-256: `1feffd961b4e86a6158a520d11582e7b0d9741a4a09071c6b5290a3bacdfe57d`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 2 (50.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 21
- Blank layout lines removed: 6
- Original routine declaration blockers: 2
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 2 (2 directly referenced)
- Exact direct sites to unknown cells: 2
- WIP compact type choices: {'BOOLEAN': 1, 'INTEGER': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
