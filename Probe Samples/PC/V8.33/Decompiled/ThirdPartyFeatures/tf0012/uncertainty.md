# TF0012 maximal KL uncertainty report

Original PC SHA-256: `587a95dfd53fdb8786fbf48def175a6464cd66ea4ac9b73bdfe2e3283d0e7505`  
KL SHA-256: `8cbcc3231d770e4e190ddafa657c7fca934245f1b037498efdf70791b242f4c9`  
Strict source completeness: **yes**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
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

- Inferred directives: TPE
- Basis: PC module dependencies and no implicit `$GROUP` link; original directive spelling remains unproved.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
