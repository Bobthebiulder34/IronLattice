# IronLattice

IronLattice is a modular, automated PCB‑fabrication platform designed to take a raw FR4 blank through milling, coating, assembly, and reflow. Built on a rigid lattice‑style frame with a multi‑tool gantry and automatic registration, IronLattice focuses on precision, repeatability, and accessible desktop‑scale PCB production.

## Features
- **Modular Tool System** — Automated tool changes for milling, cleaning, coating, dispensing, and assembly.
- **Precision Registration** — Tooling‑hole alignment and Z‑mesh compensation for both sides.
- **Pick‑and‑Place** — Tray‑based feeder, bottom‑vision alignment, and vacuum placement.
- **Controlled Reflow** — Managed preheat and localized reflow for reliable joints.
- **Flip Handling** — Safe, accurate 180° board rotation between fabrication stages.
- **Via Insertion** — Automated rivet placement with force monitoring.

## Workflow Overview
1. Milling — Two‑sided routing with height‑mesh compensation  
2. Cleaning — Brush, rinse, and dry cycles  
3. Solder Mask — Slot‑die coating and UV exposure  
4. Silkscreen — Direct‑write or flood‑cure  
5. Paste Dispensing — Auger‑based deposition  
6. Pick‑and‑Place — Tray feed → vision → placement  
7. Reflow — Bulk preheat + micro‑nozzle reflow  
8. Flip & Repeat — Second‑side processing

## Design Goals
- High repeatability  
- Modular architecture  
- Accessible workflow  
- Desktop‑friendly footprint  
- Open and hackable  

## Repository Structure
- `/mechanical` — CAD, frame layout, gantry components  
- `/electronics` — Control boards, sensors, wiring  
- `/firmware` — Gantry control and tool‑changer logic  
- `/software` — Job planner, alignment, sequencing  
- `/docs` — Build notes, diagrams, process descriptions  

## License
Choose a license that fits your goals (MIT, GPL, CERN‑OHL, etc.).

## Status
Active development. Hardware, firmware, and software components are evolving as the system matures.
