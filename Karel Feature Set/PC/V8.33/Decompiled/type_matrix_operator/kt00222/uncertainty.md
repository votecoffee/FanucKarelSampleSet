# KT00222 maximal KL uncertainty report

Original PC SHA-256: `aa0cc0c0c0bce7a4608cb315df50cfedf069d139c1655e2d6e2fd43d8b9508f9`  
KL SHA-256: `3b15bad95d1e968ee0ac8dcc43caf005a1ff92610313fed1b17f445016b1b874`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 0
- Additional unproved statements emitted as code: 2 (100.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 14
- Blank layout lines removed: 3
- Original routine declaration blockers: 0
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 0 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {}

## Unproved rendering methods used

- `bounded_indexed_byte_array_transfer`: 1 statements
- `bounded_indexed_short_array_transfer`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
