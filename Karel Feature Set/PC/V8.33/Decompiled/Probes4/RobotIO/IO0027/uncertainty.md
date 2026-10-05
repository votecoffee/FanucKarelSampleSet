# IO0027 maximal KL uncertainty report

Original PC SHA-256: `7d871a96b98035f019bcf01d491f26ccba91c5c2fa7db352c3e86bb16807dfa1`  
KL SHA-256: `d5e6a77fe0b8687c63399f96508f2d1267eb0edd66043ae6194440c5e650a6a0`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 4 (66.67% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 0
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 33
- Blank layout lines removed: 6
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 5 (3 directly referenced)
- Exact direct sites to unknown cells: 4
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 1, 'INTEGER': 1, 'REAL': 3}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 4 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\Probes4\RobotIO\IO0027\marker_fit\marker_fit.json`
