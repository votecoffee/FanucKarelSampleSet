# BZ0011 maximal KL uncertainty report

Original PC SHA-256: `24481a05c267b0d7727910dbf89f9a6df8870e4f0d84ef3a117d2b614302a456`  
KL SHA-256: `f074d5705a566ca6ce02904b32de2022fd8268a28f79e6887308fb6077502fa2`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 4
- Additional unproved statements emitted as code: 1 (20.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 19
- Blank layout lines removed: 5
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 1 (1 directly referenced)
- Exact direct sites to unknown cells: 2
- WIP compact type choices: {'INTEGER': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
