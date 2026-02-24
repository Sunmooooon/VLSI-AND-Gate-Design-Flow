### VLSI-AND-Gate-Design-Flow
## 📖 Project Overview
This project explores the implementation of a CMOS AND gate using two primary design methodologies on the **SkyWater 130nm PDK**:

* **Analog/Custom Design Approach** 🎨
\n This path focuses on transistor-level precision and manual optimization:
  - **Schematic Entry (Xschem):** Designing and implementing an AND gate at the transistor level.
  - **Pre-Layout Simulation:** Verifying the theoretical logic and timing using Ngspice before any physical implementation.
  - **Physical Layout (Magic VLSI):** Manually drawing the silicon layers, following Sky130 design rules.
  - **Parasitic Extraction:** Extracting the RC parasitics (capacitance and resistance) from the physical layout to see real-world effects.
  - **Post-Layout Simulation:** Re-simulating the extracted netlist in Ngspice to ensure the design still meets specs after considering physical interconnects.
* **Digital/Automated Flow** 🤖
    - Implementation of a full **RTL-to-GDSII** flow using **OpenLane**.
    - Automated transformation from Verilog logic descriptions into manufacture-ready physical hardware.

Both methodologies are reinforced with **Post-Layout Simulations (Ngspice)** to ensure the final designs are logically correct and compliant with foundry-specific physical design rules.

# Prequisites
for bla bla u need to download sevral prequities, sunch as
tabel
for how to download reffer to link
