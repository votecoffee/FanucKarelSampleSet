# CA0008 maximal KL uncertainty report

Original PC SHA-256: `ca1c8a5c3f16021fca54f825508a03f8d3e57c55b347b5861a767b79a71545cb`  
KL SHA-256: `fbbf0c8c4ae0c80a7c0e1e138245b2dccfa8563e74a8407b98293981cba0533f`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 9
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 2
- Explanatory comments moved to JSON report: 16
- Blank layout lines removed: 6
- Original routine declaration blockers: 0
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 0 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {}

## Unproved rendering methods used

- None.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
