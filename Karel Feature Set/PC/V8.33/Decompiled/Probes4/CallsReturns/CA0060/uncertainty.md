# CA0060 maximal KL uncertainty report

Original PC SHA-256: `57d2e2ed9f76850da430901de19c879431dce4b29f955801db8b1ab9fe15709a`  
KL SHA-256: `8ce77afbebb5157325098d68a261fd3bd29c54ac0e26b52409f71c52b69036cd`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 8
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 3
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
