# DT0059 maximal KL uncertainty report

Original PC SHA-256: `95ff655f8d9a31bfb9b24ba556e588634df61c5b0d8a32b5c7386a9c3a114764`  
KL SHA-256: `e48af912f285d23644cd70259555926e1b87720aa2cb81e8efa15371e0f5ecd4`  
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

- Inferred directives: IOSETUP
- Basis: PC module dependencies and no implicit `$GROUP` link; original directive spelling remains unproved.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
