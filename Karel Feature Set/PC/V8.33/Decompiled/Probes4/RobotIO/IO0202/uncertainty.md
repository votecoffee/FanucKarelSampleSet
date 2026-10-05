# IO0202 maximal KL uncertainty report

Original PC SHA-256: `4362bab3f6010dc26575ce41bf58b40885521e34c70e4771a534aeed6c8378a1`  
KL SHA-256: `2d2c0bbc9dc7ebc60acfb6e2989d25622dccbd504290380b85448d9d0cb29286`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 3 (60.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 30
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (3 directly referenced)
- Exact direct sites to unknown cells: 3
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 2, 'REAL': 2}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 3 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
