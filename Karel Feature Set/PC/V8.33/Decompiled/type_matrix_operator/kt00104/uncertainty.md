# KT00104 maximal KL uncertainty report

Original PC SHA-256: `d672ecf54acdf43729ee93bf4a746e2de44c17d2b7c286424d7ba600893efab2`  
KL SHA-256: `e3a78e70b5e746b051dd38e0661d28a83116d205cc05b7adf115d3d6182154cf`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 2 (66.67% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
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

- `bounded_indexed_short_array_transfer`: 2 statements
- `implicit_integer_real_expression`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\type_matrix_operator\kt00104\marker_fit\marker_fit.json`
