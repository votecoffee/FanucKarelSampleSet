# KT00087 maximal KL uncertainty report

Original PC SHA-256: `af18a7f0139f85457ebc7abd7b35b0a503be95f8ca7546e23eaff1c35b8973c7`  
KL SHA-256: `cf9df84878eadb5ed2b9d0305d2431ba42db3e1df7cfa2bf7fa8022e454febfd`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 0
- Additional unproved statements emitted as code: 3 (100.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 4
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 14
- Blank layout lines removed: 3
- Original routine declaration blockers: 0
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 0 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {}

## Unproved rendering methods used

- `bounded_indexed_byte_array_transfer`: 2 statements
- `bounded_indexed_short_array_transfer`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\type_matrix_operator\kt00087\marker_fit\marker_fit.json`
