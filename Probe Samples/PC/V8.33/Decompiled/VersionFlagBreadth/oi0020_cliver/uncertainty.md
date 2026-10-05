# OI0020 maximal KL uncertainty report

Original PC SHA-256: `1916cf202e1fee3114db3656f393a1f5c5e6a52a37bcdbe6dd46758e697d2fe3`  
KL SHA-256: `479dcf750ca997fcee1d87c94188cbe41f2f2850e872378feaf4d76a3415ad9a`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 2
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 19
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 1 (1 directly referenced)
- Exact direct sites to unknown cells: 2
- WIP compact type choices: {'INTEGER': 1}

## Unproved rendering methods used

- None.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
