# C790017 maximal KL uncertainty report

Original PC SHA-256: `8e829e323db4f4d0bccd14f0a0818543a4e4a1799a90d7812a22a2f09115f28d`  
KL SHA-256: `9324dcf37ba4871e2cd56e6ce828f06c6de48beebd6368d398d77e77d600b00d`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 11
- Additional unproved statements emitted as code: 2 (15.38% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 20
- Blank layout lines removed: 5
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 1 (1 directly referenced)
- Exact direct sites to unknown cells: 2
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'REAL': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 2 statements
- `implicit_integer_real_expression`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\KarelPCDecompileWorkingData\Probe Samples\Decompiled\PC\V8.33\Consumer79Trace\C790017\marker_fit\marker_fit.json`
