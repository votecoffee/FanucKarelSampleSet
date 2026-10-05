# CE0120 maximal KL uncertainty report

Original PC SHA-256: `064f26af01a0ea2ea0e37b9cae38473427ed200b370e0943d880f3c618db6bba`  
KL SHA-256: `aa14cc7ef00a3115a6b76c90109b52ed385415d497bad73fce6b75384c006b95`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 9
- Additional unproved statements emitted as code: 8 (47.06% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 3
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
- `bounded_string_relational_control_condition`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\Probes4\Conditions\CE0120\marker_fit\marker_fit.json`
