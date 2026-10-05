# MP0167 maximal KL uncertainty report

Original PC SHA-256: `d44b83559e38cb4791796fd526fb63b9d1eb4c47662835f22696996fcb4bbce9`  
KL SHA-256: `af4db7e1ed78037f82b96316d5af15545c929e4624888738eb77926c15ab7db3`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 8 (88.89% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 33
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 7 (6 directly referenced)
- Exact direct sites to unknown cells: 9
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'INTEGER': 6, 'REAL': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 6 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
