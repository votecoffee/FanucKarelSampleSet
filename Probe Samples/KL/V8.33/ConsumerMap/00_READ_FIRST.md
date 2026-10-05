# Consumer-side map controls

Read [the result report](../../../Evidence/ConsumerMap_2026-09-30/REPORT.md) first. `CM0001.KL`–`CM0010.KL` are ten independent V8.33-1 compiler inputs for the Consumer 4 map's indexed STRING, SELECT/return, FOR bound, and INTEGER-to-REAL examples. Their native outputs are in `../../../PC/V8.33/ConsumerMap/`; compiler logs, hashes, the 36-span boundary audit, and the 708-PC raw-record census are under `../../../Evidence/ConsumerMap_2026-09-30/`.

The sources compile without `robot.ini` using `ktrans.exe /ver V8.33-1 <file.KL>`. A matching opcode sequence identifies a candidate mechanism; it does not establish original operands, branch targets, anonymous-cell types, source spelling, or whole-PC equality. The exact raw-record matches identified in the report apply only to the bounded spans shown there.
