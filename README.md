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



## 🔹 What is RTL → GDS-II?

- **RTL (Verilog)** describes digital logic behavior  
- **GDS-II** is the final layout used for chip fabrication  
- Goal: Convert RTL → physical layout ready for manufacturing

---

## 🔹 ASIC Flow Stages (OpenLane)

1. **Synthesis** – RTL → gate-level netlist (Yosys + ABC)  
2. **Floorplanning** – Die size, core size, power grid  
3. **Placement** – Global + detailed cell placement  
4. **CTS (Clock Tree Synthesis)** – Build clock network  
5. **Routing** – Global + detailed routing (TritonRoute)  
6. **Signoff** – DRC, LVS, STA  
7. **GDS-II Generation** – Final chip layout

---

## 🔹 OpenLane Pipeline Diagram



