# KT00754 maximal KL uncertainty report

Original PC SHA-256: `4e92c3746f56d544812347bc1040faad4ec1d734dc44fb40661dcc1020fb03c5`  
KL SHA-256: `0c72d10573e1a9a709f3bbf0ea3b6f5df5c793dba90de1c3fa674587e9fcd71f`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 0
- Additional unproved statements emitted as code: 4 (100.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 4
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

- `bounded_indexed_short_array_transfer`: 4 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
