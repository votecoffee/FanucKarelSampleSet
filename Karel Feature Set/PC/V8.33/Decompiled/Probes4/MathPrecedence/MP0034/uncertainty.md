# MP0034 maximal KL uncertainty report

Original PC SHA-256: `59f226c893abb96f2d4d5470a8f3812af7d5a8eb672e8ad33f0225dc7c6a7759`  
KL SHA-256: `557d8c97ff92bbf667a52ed7a8d2b8e939dcc9bd145759a97cdbebcb2e51c2b5`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 9 (90.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 33
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 7 (6 directly referenced)
- Exact direct sites to unknown cells: 8
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'INTEGER': 3, 'REAL': 4}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 7 statements
- `bounded_scalar_expression_return`: 2 statements
- `implicit_integer_real_expression`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\Probes4\MathPrecedence\MP0034\marker_fit\marker_fit.json`
