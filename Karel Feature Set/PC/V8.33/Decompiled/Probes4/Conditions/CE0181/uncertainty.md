# CE0181 maximal KL uncertainty report

Original PC SHA-256: `9a2afd7fc2e27771e3ce727f4534a1fd285f58b3dbc31161a295df37ef508dc6`  
KL SHA-256: `9239ed3adc8275840cce06df241684a7c3b0dfd7b84a175b6c856c3bf1d0b346`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 11
- Additional unproved statements emitted as code: 5 (31.25% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 2
- Explanatory comments moved to JSON report: 23
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 3 (3 directly referenced)
- Exact direct sites to unknown cells: 3
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'INTEGER': 1, 'REAL': 2}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 3 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
