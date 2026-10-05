# IO0043 maximal KL uncertainty report

Original PC SHA-256: `b786622e7a89dd343b040ba7bc89f8d2a43dbc5ed0987d25f399b91cab2ded2d`  
KL SHA-256: `d3d73c0a74189ff20086b12a3040eeb6ca7da902d4a43f047d3039007258f2dd`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 4
- Additional unproved statements emitted as code: 2 (33.33% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 32
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (2 directly referenced)
- Exact direct sites to unknown cells: 2
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 1, 'REAL': 3}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
