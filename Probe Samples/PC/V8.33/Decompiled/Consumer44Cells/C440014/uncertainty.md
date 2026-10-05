# C440014 maximal KL uncertainty report

Original PC SHA-256: `4162a552e7905a3cd70501c38519d159f4c8d1d8dab39fe42629ab0b5bc0574f`  
KL SHA-256: `67461bd1c66616f6e2b62e2a159c0f82d7ff9f9c7067da8c4a286283cfe6551d`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 5 (83.33% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 19
- Blank layout lines removed: 5
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 1 (1 directly referenced)
- Exact direct sites to unknown cells: 5
- WIP compact type choices: {'BOOLEAN': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 5 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
