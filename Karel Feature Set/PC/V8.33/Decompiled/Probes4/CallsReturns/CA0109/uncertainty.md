# CA0109 maximal KL uncertainty report

Original PC SHA-256: `ceff6172aa0752d8c016489e7f1c9271f6c66517fbbb67ba0b18f3486c2b24c4`  
KL SHA-256: `04282eedfc5eddb84c599197a5c097985f20347fee00f8f5d343857f40c8972b`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 7
- Additional unproved statements emitted as code: 1 (12.50% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 3
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 3
- Explanatory comments moved to JSON report: 15
- Blank layout lines removed: 6
- Original routine declaration blockers: 0
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 0 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {}

## Unproved rendering methods used

- `bounded_scalar_expression_return`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
