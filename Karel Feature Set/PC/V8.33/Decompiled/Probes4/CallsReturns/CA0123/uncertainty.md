# CA0123 maximal KL uncertainty report

Original PC SHA-256: `693aeb21c6071c4bcc1d7a329004991fbad3c9bf76face0b70d06ebfbbefecb6`  
KL SHA-256: `bdc0742f97cc3c737b899502a4db22fbce59d1d36102e72314e33f1a130c92fe`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 11
- Additional unproved statements emitted as code: 3 (21.43% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 5
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 6
- Explanatory comments moved to JSON report: 16
- Blank layout lines removed: 9
- Original routine declaration blockers: 0
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 0 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {}

## Unproved rendering methods used

- `bounded_scalar_expression_return`: 3 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
