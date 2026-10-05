# DX0065 maximal KL uncertainty report

Original PC SHA-256: `09f2a310b8a675df83d160e6d750356cbc6d7ff00d0487ca0c791e465266e645`  
KL SHA-256: `5c56e140ec813d96d5aeebaba7fd36d6c315b4356fd60b73845ed0c6ece00f9f`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 2 (66.67% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 19
- Blank layout lines removed: 5
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 2 (2 directly referenced)
- Exact direct sites to unknown cells: 3
- WIP compact type choices: {'INTEGER': 2}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 2 statements
- `exact_partitioned_call_with_candidate_compact_locals`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
