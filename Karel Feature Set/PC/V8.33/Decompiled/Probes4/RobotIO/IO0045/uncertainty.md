# IO0045 maximal KL uncertainty report

Original PC SHA-256: `daa23908e863c1fb2856f54aa5c224c1ded8f1971e1fdba1a981ec0218c58426`  
KL SHA-256: `fb5fb71ccdb57bb9a14eaa6ccc98a6557ddfffdedcc733715276b0d48c58aa6e`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 4
- Additional unproved statements emitted as code: 2 (33.33% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 32
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (2 directly referenced)
- Exact direct sites to unknown cells: 2
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 1, 'REAL': 3}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
