# FW0008 maximal KL uncertainty report

Original PC SHA-256: `ad47d9294dba374c154e219de28c6e4d4bd8787403306d186dbc6e732b7b8604`  
KL SHA-256: `3d89b87323945d0d2a852d915043f9a9a15436eccecd7bcb091bbaffde998538`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 3
- Additional unproved statements emitted as code: 3 (50.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 30
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 5 (2 directly referenced)
- Exact direct sites to unknown cells: 3
- WIP compact type choices: {'BOOLEAN': 2, 'REAL': 3}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 3 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
