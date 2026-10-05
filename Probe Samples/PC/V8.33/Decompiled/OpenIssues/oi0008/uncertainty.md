# OI0008 maximal KL uncertainty report

Original PC SHA-256: `7bb3ff7e5d98e2330c8387c0fc52048e00b2bfe934530a7bdf9f29ca4666b6bb`  
KL SHA-256: `3764f55d426517d2a26f7883ac7683b9f2a52732f948c4eaf3667a7a5e0a251f`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 1 (50.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 30
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (1 directly referenced)
- Exact direct sites to unknown cells: 1
- WIP compact type choices: {'INTEGER': 1, 'REAL': 3}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
