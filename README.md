# Heart-LED-Project
Heart-shaped LED badge with integrated Li-ion battery charging system.

A self-initiated project to bridge the gap between theory and hardware. I designed, routed, and hand-assembled this PCB from scratch. It’s a portable, rechargeable system featuring:

Power: Portable system featuring a Li-ion battery with an integrated charging circuit (TP4056).

Architecture: Discrete LED array driven by an NE555 timer on a custom-shaped, double-layer PCB.

Toolchain: KiCad 9.0.

What I Learned:

End-to-End Workflow: Moved from theory to a physical product by managing the full cycle: footprints, BOM, and Gerber generation for manufacturing.

Component Selection: Mastered reading datasheets to select appropriate ICs, like the TP4056 for charging and the NE555 timer for logic.

DFA (Design for Assembly): Implemented HandSolder footprints with enlarged pads to ensure reliable manual assembly and easier debugging.

Power Integration: Gained practical experience with Li-ion battery management and USB power standards.

Possible Improvements:

Battery Safety: V1.0 focuses on the charging cycle. In the next iteration, I will add a DW01A protection IC and 8205A MOSFETs to prevent undervoltage (below 2.4V) and ensure battery longevity.


