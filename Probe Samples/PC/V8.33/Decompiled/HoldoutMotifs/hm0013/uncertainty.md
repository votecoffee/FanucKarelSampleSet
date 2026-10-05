# HM0013 maximal KL uncertainty report

Original PC SHA-256: `44dd82c2a11796c3828a049de8d58d037c8b0b2164f353495005fe40161826bb`  
KL SHA-256: `485ae7ec7744ff203ab8fb7754cb35ebe9e84a05bcfa9b594d829130cc034cb5`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 3 (60.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 26
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 3 (2 directly referenced)
- Exact direct sites to unknown cells: 4
- WIP compact type choices: {'BOOLEAN': 2, 'REAL': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 3 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
