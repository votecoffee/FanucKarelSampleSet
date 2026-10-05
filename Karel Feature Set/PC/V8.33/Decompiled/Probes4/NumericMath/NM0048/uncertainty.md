# NM0048 maximal KL uncertainty report

Original PC SHA-256: `647639075c9a9bfb5e55ffb0e0ae342b011e32a1852414e421b16f2d1de33568`  
KL SHA-256: `1ff39071969181c46410dc19bb9f3df437dbe7fa3a9b6fd52b07f19b16c635aa`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 4
- Additional unproved statements emitted as code: 7 (63.64% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 24
- Blank layout lines removed: 7
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 5 (5 directly referenced)
- Exact direct sites to unknown cells: 6
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 2, 'INTEGER': 2, 'REAL': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 5 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
