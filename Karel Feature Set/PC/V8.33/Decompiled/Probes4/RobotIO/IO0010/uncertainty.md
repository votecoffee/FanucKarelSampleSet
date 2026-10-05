# IO0010 maximal KL uncertainty report

Original PC SHA-256: `6179deb4b41da7ba6b7e0e460889d7a0212af5e20d3d46909266dd8ba3ebee99`  
KL SHA-256: `b1f048d097f8b5567448ea873fc11202944d8c27c078a4178ecdbbab3f3ef031`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 3 (60.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 33
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 5 (3 directly referenced)
- Exact direct sites to unknown cells: 5
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'INTEGER': 2, 'REAL': 3}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 3 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
