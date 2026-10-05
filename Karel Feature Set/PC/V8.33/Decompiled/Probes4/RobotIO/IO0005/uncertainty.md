# IO0005 maximal KL uncertainty report

Original PC SHA-256: `9287ac31fb50281082042a3b084790b42cae979d818192d840dda94f9444b120`  
KL SHA-256: `9785a57dd33cbff3cd905b150e836f6fb72f6b870c052a3b7d3c34868d7ada00`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 5
- Additional unproved statements emitted as code: 2 (28.57% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 32
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (2 directly referenced)
- Exact direct sites to unknown cells: 2
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 1, 'REAL': 3}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\Probes4\RobotIO\IO0005\marker_fit\marker_fit.json`
