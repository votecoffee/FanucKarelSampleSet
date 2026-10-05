# MP0118 maximal KL uncertainty report

Original PC SHA-256: `83fc90ecc59c3bc58ee197dd5d58b8a368670ea6a99829394ef4ef88be529126`  
KL SHA-256: `029d58b6fe72b2fadc3be44f6538566bad88c8ea9236f6fe4dfe4388fc8917c1`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 9 (90.00% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 34
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 8 (7 directly referenced)
- Exact direct sites to unknown cells: 10
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
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\Probes4\MathPrecedence\MP0118\marker_fit\marker_fit.json`
