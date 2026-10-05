# NM0029 maximal KL uncertainty report

Original PC SHA-256: `f39c241af88a05aa15123f3510bf6eb455959449b3a2daf3c3d40bec2d259e7f`  
KL SHA-256: `5d401fcd8959f48a281c85adfb01736ec0068856c4b24fccda38ed93833166b1`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 5
- Additional unproved statements emitted as code: 7 (58.33% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 3
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 0
- Explanatory comments moved to JSON report: 23
- Blank layout lines removed: 7
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 4 (4 directly referenced)
- Exact direct sites to unknown cells: 5
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'BOOLEAN': 1, 'INTEGER': 2, 'REAL': 1}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 5 statements
- `bounded_scalar_abs_assignment`: 1 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.

## Source-marker layout

- Compiler comparison: whole_pc_equal; original source text is not authenticated.
- Filler decisions and validation: `C:\~LocalWork\Repos\Programming\~Github\KarelPCDecompileSampleSet\Karel Feature Set\PC\V8.33\Decompiled\Probes4\NumericMath\NM0029\marker_fit\marker_fit.json`
