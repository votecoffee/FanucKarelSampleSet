# FY0017 maximal KL uncertainty report

Original PC SHA-256: `7d2ebb52fa3614f8553fe4f49c16c0c8659b33450de411f439e45c47033c8018`  
KL SHA-256: `7141551aaa23dc95aa4d7bf256d1dea886af602b3384e7fae2a49719da64c7d0`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 2
- Remaining unsafe source expressions in comments: 2
- Explanatory comments moved to JSON report: 16
- Blank layout lines removed: 5
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 1
- Unknown compact 2C cells: 1 (1 directly referenced)
- Exact direct sites to unknown cells: 3
- WIP compact type choices: {}

## Unproved rendering methods used

- None.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
