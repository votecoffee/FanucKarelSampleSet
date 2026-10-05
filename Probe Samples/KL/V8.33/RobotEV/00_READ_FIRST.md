# Robot_1 EV definition probes — read first

This set exercises all 17 additional `.EV` definitions found in the `Robot_1/support` directory inside `25735 GM Lockport - Block Press.zip`. Read the [campaign report](../../../Evidence/RobotEV_2026-09-30/REPORT.md) for compiler results and the bounded comparison with the WIP971 80-cell census.

Use [PROBE_INDEX.csv](PROBE_INDEX.csv) to choose a source. `EV0001`–`EV0015` use a named type from each of the 15 non-routine EVs; `EV0016`–`EV0027` call routines defined by `DAQ.EV` or `TPGL.EV`; `EV0028` and `EV0029` are intentional rejecting controls. Successful native PCs live in `PC/V8.33/RobotEV/`. Each case's compiler logs and SHA-256 hashes are in the [manifest](../../../Evidence/RobotEV_2026-09-30/manifest.json).

The [EV inputs](../../../Evidence/RobotEV_2026-09-30/EV/) are byte-for-byte copies of the 17 ZIP members. The [builder](../../../Evidence/RobotEV_2026-09-30/build_robot_ev_probes.py) uses an isolated copy of the installed V8.33 support folder plus those definitions. `DAQ.EV` embeds environment name `PBDAQ`; the builder makes an isolated `PBDAQ.EV` alias so KTRANS can select it. Dollar-prefixed system environments are loaded without an explicit `%ENVIRONMENT` directive. Nothing is written into the installed FANUC folders.

The [relationship analysis](../../../Evidence/RobotEV_2026-09-30/relationship_analysis.json) includes native allocation records, original-PC checksums, all 169 target external references, and comparisons to the 36 target routines with unknown 2C cells. Matching a compact allocation count does **not** identify a source type or establish that the EV was used to compile the original PC.
