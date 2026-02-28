# picorv32 OpenLane Physical Design (SKY130)

## 📖 Project Overview

This project demonstrates the complete RTL-to-GDSII physical design flow of the **picorv32 RISC-V core** using the OpenLane automated ASIC flow with the SKY130 PDK.

The design flow includes synthesis, floorplanning, placement, clock tree synthesis (CTS), routing, signoff checks (DRC/LVS), and final GDSII generation.

This project was implemented to understand the full ASIC physical design flow and OpenLane toolchain in a practical environment.

---

## 🛠 Tools & Technology Used

- OpenLane Flow
- OpenROAD
- Yosys (Synthesis)
- Magic (DRC & Layout View)
- KLayout (GDSII Viewer)
- SKY130 PDK
- Ubuntu (WSL Environment)

---

## 🚀 Design Flow Stages

1. RTL Synthesis  
2. Floorplanning  
3. Placement  
4. Clock Tree Synthesis (CTS)  
5. Routing  
6. Signoff (DRC/LVS)  
7. GDSII Generation  

---

## 📂 Project Structure
picorv32-openlane-physical-design/
│
├── rtl/
│   └── picorv32.v                 # RTL source file
│
├── gds/
│   ├── picorv32.klayout.gds       # Final GDSII layout
│   ├── picorv32.sdf               # Post-layout timing file
│   ├── picorv32.lib               # Timing library file
│   └── picorv32.lyp               # KLayout layer properties
│
├── reports/
│   └── timing_summary.txt         # Extracted timing report summary
│
├── docs/
│   ├── 01_synthesis_floorplan_placement.png
│   ├── 02_routing_stage.png
│   └── 03_final_gds_layout.png
│
├── config.json                    # OpenLane configuration file
│
└── README.md                      # Project documentation
---

## 📊 Flow Stage Results

### 1️⃣ Synthesis, Floorplan & Placement
![Synthesis Floorplan Placement](docs/01_synthesis_floorplan_placement.png)

---

### 2️⃣ Routing Stage
![Routing Stage](docs/02_routing_stage.png)

---

### 3️⃣ Final GDSII Layout
![Final GDS Layout](docs/03_final_gds_layout.png)

---

## ✅ Signoff Summary

- Synthesis: Completed Successfully  
- Floorplanning: Completed Successfully  
- Placement: Completed Successfully  
- CTS: Completed Successfully  
- Routing: Completed Successfully  
- DRC: Clean  
- LVS: Clean  
- Final GDSII: Generated Successfully  

---

## 🎯 Learning Outcomes

- Understood complete RTL-to-GDSII ASIC flow
- Learned OpenLane automation flow
- Analyzed synthesis, timing, and routing reports
- Generated final GDSII layout using SKY130 PDK
- Performed signoff verification checks

---

## 📌 Conclusion

This project demonstrates a full ASIC physical design implementation of a RISC-V core using open-source tools and PDK. It provides hands-on exposure to real physical design stages used in the semiconductor industry.

---

## 👩‍💻 Author

Rajyalakshmi  
VLSI Physical Design Enthusiast
