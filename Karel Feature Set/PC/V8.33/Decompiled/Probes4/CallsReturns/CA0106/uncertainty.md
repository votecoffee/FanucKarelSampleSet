# CA0106 maximal KL uncertainty report

Original PC SHA-256: `44566efc0e22dd8ac806b35e3013a89b396ae96edac96f7b1495313d69f1a90a`  
KL SHA-256: `8652c58b0f3f5a578c681a5703b4d6b9eaa2505a51ddd1e233425e1b1bdbea98`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 8
- Additional unproved statements emitted as code: 1 (11.11% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 3
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 2
- Explanatory comments moved to JSON report: 15
- Blank layout lines removed: 6
- Original routine declaration blockers: 0
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 0 (0 directly referenced)
- Exact direct sites to unknown cells: 0
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {}

## Unproved rendering methods used

- `bounded_scalar_expression_return`: 1 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
