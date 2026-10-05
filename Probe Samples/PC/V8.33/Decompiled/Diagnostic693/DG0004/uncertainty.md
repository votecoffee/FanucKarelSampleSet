# DGCASE maximal KL uncertainty report

Original PC SHA-256: `fa664bc52165ab7be90776e06d0e1ef648fd0d7b04b164861771a177c4bdb517`  
KL SHA-256: `ca298cc95944c5582b1b330e5a9aa865cee90145556f790f8e4f61532236788d`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 0 (0.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 46
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 11 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- WIP compact type choices: {'REAL': 11}

## Unproved rendering methods used

- None.

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
