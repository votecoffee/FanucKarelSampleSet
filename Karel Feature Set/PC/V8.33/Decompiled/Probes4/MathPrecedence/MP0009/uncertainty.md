# MP0009 maximal KL uncertainty report

Original PC SHA-256: `0bc3eb19d32fbddde6ffd3cdc4073d20b6bad4b851faaa368311707b1eb387c1`  
KL SHA-256: `e8cee6800d1121012ebebbda6eef6556b79af9433b9101ec0d6888eb54e5981b`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 4
- Additional unproved statements emitted as code: 6 (60.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 31
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 5 (4 directly referenced)
- Exact direct sites to unknown cells: 4
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'INTEGER': 1, 'REAL': 4}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 4 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\Probes4\MathPrecedence\MP0009\marker_fit\marker_fit.json`
