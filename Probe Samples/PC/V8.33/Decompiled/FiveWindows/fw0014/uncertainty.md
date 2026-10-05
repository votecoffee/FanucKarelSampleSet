# FW0014 maximal KL uncertainty report

Original PC SHA-256: `ac6932d4742cd765e94232c28675d21c5d5dc8f5380aa39f319a91f4b63bb9c9`  
KL SHA-256: `b04b7d76883a497b7ab44ebdfff86db0c4c9dbf28df3210d93c63bcd4c5ff243`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 4
- Additional unproved statements emitted as code: 4 (50.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 31
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 5 (2 directly referenced)
- Exact direct sites to unknown cells: 4
- WIP compact type choices: {'BOOLEAN': 2, 'REAL': 3}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 4 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
