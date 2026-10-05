# WC0040 maximal KL uncertainty report

Original PC SHA-256: `5c3ad7bb9f8ee0772a8368ea67580c77fb7bcfac37ebc36fc987a3c815d0b739`  
KL SHA-256: `5c31518b919c5f5cc1847013288469109fa4eb5c3665a6ec998143cf2360c166`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 26
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 1 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- WIP compact type choices: {'REAL': 1}

## Unproved rendering methods used

- None.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
