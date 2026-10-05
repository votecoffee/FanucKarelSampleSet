# HM0028 maximal KL uncertainty report

Original PC SHA-256: `828a102ce91408341b3eb0cb9993a684e20c3124bbdefb645e9cce092dceb588`  
KL SHA-256: `8f66f758e427caea3b0e8182a6f150396e657777957944b702b8d81b9f247b27`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 1 (50.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 19
- Blank layout lines removed: 5
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 1 (1 directly referenced)
- Exact direct sites to unknown cells: 1
- WIP compact type choices: {'INTEGER': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 1 statements
- `exact_partitioned_call_with_candidate_compact_locals`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
