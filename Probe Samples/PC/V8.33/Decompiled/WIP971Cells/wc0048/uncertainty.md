# WC0048 maximal KL uncertainty report

Original PC SHA-256: `acdefa2229d51e3db9d0303c87faac7b67f5d62e9636954b991ed3990d2ed7e3`  
KL SHA-256: `3edc17e673170ed2ead9d212e037a55d0d24f214d648a989c6803a4db41f3a6f`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 2
- Explanatory comments moved to JSON report: 28
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 3 (1 directly referenced)
- Exact direct sites to unknown cells: 2
- WIP compact type choices: {'INTEGER': 1, 'REAL': 2}

## Unproved rendering methods used

- None.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
