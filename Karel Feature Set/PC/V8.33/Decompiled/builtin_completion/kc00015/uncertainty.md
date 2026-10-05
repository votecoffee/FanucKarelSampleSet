# KC00015 maximal KL uncertainty report

Original PC SHA-256: `e1f23360462502db163db3f1f62bbdf5beaf06c35ff322e793433b6c2c4e958f`  
KL SHA-256: `22b3883286dae78997238df568ef8dd951b5445026cb380fe3dacf4c5caf8064`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 14
- Blank layout lines removed: 4
- Original routine declaration blockers: 0
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 0 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {}

## Unproved rendering methods used

- None.

## Environment source hypothesis

- Inferred directives: REGOPE
- Basis: PC module dependencies and no implicit `$GROUP` link; original directive spelling remains unproved.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
