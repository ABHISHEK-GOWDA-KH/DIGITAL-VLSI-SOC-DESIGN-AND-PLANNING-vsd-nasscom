# DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING-vsd-nasscom
2 Week digital VLSI SoC design and planning workshop with complete RTL2GDSII flow organised by VSD in collaboration with NASSCOM
Welcome to the OpenLane workshop! In this workshop, we will delve into the process of designing an Application Specific Integrated Circuit (ASIC) from the Register Transfer Level (RTL) to the Graphical Data System (GDS) file using the OpenLane ASIC flow. The flow is composed of several key steps, starting with an RTL file and culminating in a GDS file.
## DAY 1
The RTL to GDSII flow is a process in VLSI design that converts an RTL
description of a digital circuit into a physical layout ready for fabrication. It
involves stages like RTL synthesis, floor planning, placement, routing, and
ultimately generating the GDSII file format, which contains the layout data.
This meticulous process ensures the final IC layout accurately reflects the
desired functionality and meets fabrication requirements
<img width="945" height="495" alt="image" src="https://github.com/user-attachments/assets/96c0d8f8-96de-4ca3-a562-7607f9084cbd" />
#  Day 1

RTL to GDSII is the complete digital ASIC design flow that converts a Verilog/VHDL Register Transfer Level (RTL) description into a final GDSII layout ready for fabrication. The process begins with RTL design and functional verification. Then synthesis converts RTL into a gate-level netlist using standard cell libraries. Floorplanning defines the chip area, power grid, placement constraints, and major block locations. Power planning adds power straps and rings. Placement arranges standard cells and optimizes timing. Clock Tree Synthesis (CTS) builds and balances the clock network to reduce skew. Routing connects all signals using metal layers while obeying design rules. After routing, physical verification checks for DRC (design rule check) and LVS (layout vs. schematic) correctness. Timing signoff ensures all paths meet setup/hold requirements. Finally, the design is exported as a GDSII file, which is the mask-level layout delivered to the foundry for chip fabrication.








