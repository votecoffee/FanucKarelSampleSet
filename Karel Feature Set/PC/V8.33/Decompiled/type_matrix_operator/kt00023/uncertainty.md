# KT00023 maximal KL uncertainty report

Original PC SHA-256: `ef82b2ed6568d1f5724ecb8609d5a0812b2270710ee89ea92f8e3dca2c2d029c`  
KL SHA-256: `31f8c7888b6a2291346e2c67ab19c43426c9dab70e875d3855b896a5d06a0f6f`  
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
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\type_matrix_operator\kt00023\marker_fit\marker_fit.json`
