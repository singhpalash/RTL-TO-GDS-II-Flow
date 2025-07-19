# RTL-TO-GDS-II-Flow
Physical Design of Sequential ALU

### 🗂️ Table of Contents
1) Project Objectives
2) Design Specifications
3) RTL-to-GDSII Flow Steps
4) Learnings
5) Conclusion

### 📌 Project Objectives
1) Design and verify a 4-bit sequential Arithmetic Logic Unit (ALU) at RTL level.

2) Perform complete ASIC physical design flow, including synthesis, floorplanning, placement, CTS, routing, and signoff.

3) Generate a clean GDSII layout passing all physical and logical verification checks.

### 🏗️ Design Specifications
1) ALU Width: 4 bits

2) Sequential Design: Operates over multiple clock cycles using control signals

3) Clock Frequency Target: ~100 MHz (adjustable)

4) Technology Node: 180 nm standard cell library 

### 🚀 RTL-to-GDSII Flow Steps

#### 1) RTL Design & Simulation

- Developed Verilog code for ALU and testbench.

- Verified functionality via simulation.

#### 2) Synthesis

- Performed synthesis with timing constraints.

- Generated gate-level netlist and SDC.

#### 3) Floorplanning & Power Planning

- Defined die/core area, IO placement.

- Inserted power rings and stripes.

#### 4) Placement & CTS

- Standard cell placement and legalization.

- Clock tree synthesized with minimal skew.

#### 5) Routing

- Completed global and detailed routing.

- Ensured DRC-clean layout.

#### 6) Signoff Checks

- Static Timing Analysis (STA): Met setup/hold requirements.

- DRC/LVS: Cleaned the violations.

- Power Analysis - There was no major power leakage or dissipation spots

#### 7) GDSII: Final layout file ready for tapeout.

### Tools and Technologies
- Synthesis- Cadence Genus
- Physical Design - Cadence Innovus
- Signoff Timing - Cadence Tempus
- Signoff Power - Cadence Voltus


### 📚 Learnings
- Understood the full RTL to GDSII flow used in ASIC industry.

- Gained hands-on experience with EDA tools and scripting.

- Learned critical concepts like clock tree synthesis, congestion handling, and timing closure.

### 🏁 Conclusion
- This project represents a tapeout-ready design of a small yet functional ALU. It provided an end-to-end understanding of physical design and its challenges  making it ideal for students aiming for roles in Physical Design, RTL to GDSII, or Backend VLSI.




