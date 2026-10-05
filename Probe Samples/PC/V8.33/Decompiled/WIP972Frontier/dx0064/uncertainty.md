# DX0064 maximal KL uncertainty report

Original PC SHA-256: `f9047ee4edcbe9107ff8c98e4d6c40685d01841a47f95fc58c81bb546503aa3a`  
KL SHA-256: `d5894e3846643985e0c3607cb491ec187945ebe7b1bff526fb99e6931712b451`  
Strict source completeness: **yes**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 3
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 7
- Blank layout lines removed: 4
- Original routine declaration blockers: 0
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 0 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- WIP compact type choices: {}

## Unproved rendering methods used

- None.

## Environment source hypothesis

- Inferred directives: REGOPE
- Basis: PC module dependencies and no implicit `$GROUP` link; original directive spelling remains unproved.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
