# BZ0009 maximal KL uncertainty report

Original PC SHA-256: `55581316509e8d96698020f6b7692e5b9a67f548c92cc6a363ad574325b9ac85`  
KL SHA-256: `150e50f44f8258763f62ce6e68412703f8f3006ae2ad4c7180709f216ed31c32`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 3
- Additional unproved statements emitted as code: 1 (25.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 27
- Blank layout lines removed: 7
- Original routine declaration blockers: 2
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 2 (1 directly referenced)
- Exact direct sites to unknown cells: 1
- WIP compact type choices: {'BOOLEAN': 1, 'REAL': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
