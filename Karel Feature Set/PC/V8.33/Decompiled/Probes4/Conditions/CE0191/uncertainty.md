# CE0191 maximal KL uncertainty report

Original PC SHA-256: `f28d1ba5505ba3a37746ba4048a81538f36f9fbb3df3221bf1768ae86d82efa6`  
KL SHA-256: `b20c400c35d04193eb984f175f0523864f63746d51cdc202737c5cb357ee1e7d`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 10
- Additional unproved statements emitted as code: 6 (37.50% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 24
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (4 directly referenced)
- Exact direct sites to unknown cells: 4
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 2, 'INTEGER': 1, 'REAL': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 4 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
