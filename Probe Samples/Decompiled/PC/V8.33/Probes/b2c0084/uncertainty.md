# B2C0084 maximal KL uncertainty report

Original PC SHA-256: `6368c0f4c015dc9174177cf087949bd767cc50a0fc1db21338e3e37f14a01808`  
KL SHA-256: `6041c5fced63181ae42be658f2231b9c2f96b833098643be84e5abbb04b1a414`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 1
- Additional unproved statements emitted as code: 2 (66.67% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 1
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
- `bounded_scalar_real_reference_intrinsic`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\KarelPCDecompileWorkingData\Probe Samples\Decompiled\PC\V8.33\Probes\b2c0084\marker_fit\marker_fit.json`
