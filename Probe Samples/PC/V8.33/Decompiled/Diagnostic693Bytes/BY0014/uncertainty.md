# BYTEPROBE maximal KL uncertainty report

Original PC SHA-256: `a49564e654d8e975db92183c8df18fa6ef081e1b88b9ce75420b8f938f0c0323`  
KL SHA-256: `ab827f25335b346172db10201c2d392396ccbad437daa682ca7aeaaec816c36f`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 1
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
