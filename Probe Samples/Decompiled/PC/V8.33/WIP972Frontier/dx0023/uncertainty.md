# DX0023 maximal KL uncertainty report

Original PC SHA-256: `bf958814cd1ef823f8a8480bffc828f35d247a57195dc57cf173ef2298ddb0b5`  
KL SHA-256: `19b2ba35986c72fd0ac5f180d43efa4226f318d690f9bfe99711897d30d60868`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 4 (66.67% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 21
- Blank layout lines removed: 5
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 2 (2 directly referenced)
- Exact direct sites to unknown cells: 4
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'INTEGER': 2}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 4 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\KarelPCDecompileWorkingData\Probe Samples\Decompiled\PC\V8.33\WIP972Frontier\dx0023\marker_fit\marker_fit.json`
