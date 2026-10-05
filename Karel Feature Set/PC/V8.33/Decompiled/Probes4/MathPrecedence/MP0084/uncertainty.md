# MP0084 maximal KL uncertainty report

Original PC SHA-256: `07f8871aed60cfe82e690210635d7069270e964b52d6d704ac08ef084ea6721e`  
KL SHA-256: `52d9d5e922542b87514033b43a3ac5dd3ba48d5056aa73aeed7bacc06498890c`  
Strict source completeness: **no**.  
This KL is a reconstruction candidate. Compilation does not establish original behavior or deployment safety.

## Coverage

- Statements from existing source-safe renderer: 2
- Additional unproved statements emitted as code: 7 (77.78% of emitted statements)
- Existing-renderer statements with explicitly unproved rules: 2
- Guarded compact STRING concat source spellings (unproved original spelling): 0
- Remaining unresolved PC spans in comments: 0
- Remaining unsafe source expressions in comments: 1
- Explanatory comments moved to JSON report: 32
- Blank layout lines removed: 8
- Original routine declaration blockers: 1
- Routine declaration warnings in comments: 0
- Unknown compact 2C cells: 6 (5 directly referenced)
- Exact direct sites to unknown cells: 6
- Routines without located compact-cell geometry: 0
- Unknown compact cells without known frame offsets: 0
- WIP compact type choices: {'INTEGER': 2, 'REAL': 4}

## Unproved rendering methods used

- `assumed_compact_2c_source_type`: 5 statements
- `bounded_scalar_expression_return`: 2 statements

The companion JSON lists every emitted unproved statement, remaining comment,
unknown-cell alternative, and original-PC local-reference site with code offset.
Source-safe here means accepted by the maintained renderer; it does not mean
the original source spelling or whole-PC equality has been recovered.
