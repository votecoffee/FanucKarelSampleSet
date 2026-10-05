# NM0041 maximal KL uncertainty report

Original PC SHA-256: `7aad8b53db5fe965d82bba358544fedf851c2b7a649a6b423d239fe9c6770f5b`  
KL SHA-256: `56bd1e963b72613b22d3ebabe3e885882c601d754847c8f19c7753eb3355e970`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 6
- Additional unproved statements emitted as code: 5 (45.45% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 22
- Blank layout lines removed: 7
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 3 (3 directly referenced)
- Exact direct sites to unknown cells: 3
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 1, 'INTEGER': 1, 'REAL': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 3 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
