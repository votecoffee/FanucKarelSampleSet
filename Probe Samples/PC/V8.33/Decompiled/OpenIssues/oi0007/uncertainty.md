# OI0007 maximal KL uncertainty report

Original PC SHA-256: `4dd2e63159e44bc2854663c78e24940956e7cc7d81015d98489bf2d943912807`  
KL SHA-256: `3c30d4658d119dd46f24cd29642516d85f761527831a1c5311779a8c433b6dba`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 1 (50.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 30
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (1 directly referenced)
- Exact direct sites to unknown cells: 1
- WIP compact type choices: {'INTEGER': 1, 'REAL': 3}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
