# CE0051 maximal KL uncertainty report

Original PC SHA-256: `d7814b2355835f3c44b16e8ac93ce9c963d06f4653c33fe716af4b0ef3f753c4`  
KL SHA-256: `db11b1043a25675b7f4b9b719d46ff199e1654616df18076a6d840901a7a2d1b`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 10
- Additional unproved statements emitted as code: 7 (41.18% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 1
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 25
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 5 (5 directly referenced)
- Exact direct sites to unknown cells: 5
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 2, 'INTEGER': 1, 'REAL': 2}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 5 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\Probes4\Conditions\CE0051\marker_fit\marker_fit.json`
