# CE0188 maximal KL uncertainty report

Original PC SHA-256: `2543679f06c7918b3c698ccffc0c77b610db294d206bf88edcd42c47e4dc8f2e`  
KL SHA-256: `b8d4a7bf53dee5449c91795ab76f808f20a804b3affe1625f953c6522ca152f5`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 10
- Additional unproved statements emitted as code: 6 (37.50% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 2
- Explanatory comments moved to JSON report: 24
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (4 directly referenced)
- Exact direct sites to unknown cells: 5
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 1, 'INTEGER': 1, 'REAL': 2}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 4 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
