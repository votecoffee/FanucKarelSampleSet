# Open-issue V8.33 probes

Start with the [campaign report](../../../Evidence/OpenIssues_2026-09-30/REPORT.md). The [index](PROBE_INDEX.csv) maps all **28 compiler-accepted KL controls** to their issue family, compiled PC, hashes, and guarded decompiler-candidate compile status. Native PCs are in [`PC/V8.33/OpenIssues`](../../../PC/V8.33/OpenIssues/).

The sources cover erased 2C types, storage ownership and order, ambiguous uses, valid structural controls, custom aggregates, partial IF/SELECT syntax, and executable STRING/FILE/WAIT/position/call cases. These are synthetic controlled inputs. The separate [corrupt-control manifest](../../../Evidence/OpenIssues_2026-09-30/corrupt_controls/manifest.json) records four CRC-coherent synthetic PC mutations; they were never KTRANS outputs and are kept outside the `PC/` sample tree.
