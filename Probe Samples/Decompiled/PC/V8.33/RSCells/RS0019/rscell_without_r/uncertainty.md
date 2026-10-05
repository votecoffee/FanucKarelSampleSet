# RSCELL maximal KL uncertainty report

Original PC SHA-256: `39cafa38b2f64dbfb1312d5def2df8076c1b9734f93b9237dc0cf22e21a96bbf`  
KL SHA-256: `eb9b64a71f27f0169f0e19e18084a86875a11c024f5216d6dbec8da0d75f14ea`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 1 (33.33% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 30
- Blank layout lines removed: 7
- Original routine declaration blockers: 2
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 2 (1 directly referenced)
- Exact direct sites to unknown cells: 1
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 1, 'REAL': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\KarelPCDecompileWorkingData\Probe Samples\Decompiled\PC\V8.33\RSCells\RS0019\rscell_without_r\marker_fit\marker_fit.json`
