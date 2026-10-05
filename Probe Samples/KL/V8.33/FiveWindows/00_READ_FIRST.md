# V8.33 five-opcode window probes

Start with the [results report](../../../Evidence/FiveWindows_2026-09-30/REPORT.md), then use [PROBE_INDEX.csv](PROBE_INDEX.csv) to locate each `FWnnnn.KL` and its `PC/V8.33/FiveWindows/fwnnnn.pc` output. [The manifest](../../../Evidence/FiveWindows_2026-09-30/manifest.json) contains hashes and compiler logs; [the window analysis](../../../Evidence/FiveWindows_2026-09-30/window_analysis.json) connects the 21 original local-reference sites to matching controlled probes.

The 23 programs vary IF/ELSE, FOR, WHILE, SELECT, indexed-DIN WAIT, STRING assignment, and VECTOR copy directly before or after an INTEGER zero comparison or local store. All compiled with KTRANS V8.33 Build 25 in isolated scratch directories using `/ver V8.33-1`. The installed FANUC compiler and original PCs were read only. Five-opcode matching is diagnostic; it does not recover an original cell's type or source declaration.
