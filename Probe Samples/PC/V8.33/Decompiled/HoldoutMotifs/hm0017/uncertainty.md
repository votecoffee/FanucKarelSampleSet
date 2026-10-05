# HM0017 maximal KL uncertainty report

Original PC SHA-256: `49f57d3013fd3a11f4f273669d0d0bc49961bcccfd0b71156a7b756c51a9bf61`  
KL SHA-256: `11ed95f4c1db55581ffe128f885d38e814543360503261d112e38a4c7e3df69f`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 4 (80.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 19
- Blank layout lines removed: 5
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 2 (2 directly referenced)
- Exact direct sites to unknown cells: 5
- WIP compact type choices: {'BOOLEAN': 1, 'INTEGER': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 4 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
