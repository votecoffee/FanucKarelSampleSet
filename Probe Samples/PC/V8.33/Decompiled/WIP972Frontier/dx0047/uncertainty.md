# DX0047 maximal KL uncertainty report

Original PC SHA-256: `286afe85c08df09a54a63be1b87ba06efbfbe9496a69887e2a52b11d3e159455`  
KL SHA-256: `cca669a6560c60517406a414ecdb07a97d7654480970e535f2430eb59e275229`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
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
