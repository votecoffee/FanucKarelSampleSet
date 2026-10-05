# BZ0015 maximal KL uncertainty report

Original PC SHA-256: `70390ed9283bb549b8aca456abcefddb90197b7c797d2e8efcd3fe32a79fffed`  
KL SHA-256: `cc9c489627bc7257649925b352db18bfc5d3eccdcf1d174d0f6ba16b033780a3`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 3
- Additional unproved statements emitted as code: 1 (25.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 29
- Blank layout lines removed: 7
- Original routine declaration blockers: 2
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 3 (1 directly referenced)
- Exact direct sites to unknown cells: 1
- WIP compact type choices: {'BOOLEAN': 1, 'REAL': 2}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
