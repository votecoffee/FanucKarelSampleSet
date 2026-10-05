# CA0121 maximal KL uncertainty report

Original PC SHA-256: `08699786bd99495f8229ed6ac9757b5a3e1f4d1e18b098a670cb8b304f24726c`  
KL SHA-256: `e341f56c5d3fdfa951ab57b5d18814ddc5bccbdb08494118e385bd1d2fa32380`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 11
- Additional unproved statements emitted as code: 3 (21.43% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 5
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 6
- Explanatory comments moved to JSON report: 16
- Blank layout lines removed: 9
- Original routine declaration blockers: 0
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 0 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {}

## Unproved rendering methods used

- `bounded_scalar_expression_return`: 3 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
