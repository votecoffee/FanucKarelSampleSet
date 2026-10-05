# WC0033 maximal KL uncertainty report

Original PC SHA-256: `b66688dd2217efa99b30b42f5f06e0178eff2d08a5aaaecb98d8c5118d3f4320`  
KL SHA-256: `594dd0dc8092f229d2da95e4cf623a763c35b0ac5c47bfc25622f6dc78f6b1b6`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 32
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- WIP compact type choices: {'REAL': 4}

## Unproved rendering methods used

- None.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
