# IO0194 maximal KL uncertainty report

Original PC SHA-256: `2e0f8af87f9dfc8b99ce94e17f6d18242f35f8f9f3ff32a038f0efe12ff3b231`  
KL SHA-256: `f0053277ea13c256279a257276641e8ce2a9c261c46493df6a42f8e7d46f0e4f`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 4
- Additional unproved statements emitted as code: 2 (33.33% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 29
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 3 (2 directly referenced)
- Exact direct sites to unknown cells: 2
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 1, 'REAL': 2}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
