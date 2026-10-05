# MP0073 maximal KL uncertainty report

Original PC SHA-256: `5b31c13dd4157377160d0bfa7fec01db95406a52f5ab1e28167cd033c856114c`  
KL SHA-256: `3db449ef07a19d9c87fb79c9cba607f66a319caba644fadf1b11fe81bfdba051`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 9 (81.82% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 34
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 8 (7 directly referenced)
- Exact direct sites to unknown cells: 8
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'INTEGER': 4, 'REAL': 4}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 7 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\Probes4\MathPrecedence\MP0073\marker_fit\marker_fit.json`
