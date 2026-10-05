# CA0088 maximal KL uncertainty report

Original PC SHA-256: `7204e7291f62eab8e42e6e8b4954bf4c5c7ac670e2a20c1dc3890ef56dad5dff`  
KL SHA-256: `9a0172436a1cf315a77969f18d1bb2142459c557f374b9ad8cd3d0dbae8ef177`  
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
