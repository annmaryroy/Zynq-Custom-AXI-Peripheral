# Custom AXI4-Lite Peripheral Design using Zynq SoC

## Overview
This project demonstrates the design and integration of a **custom AXI4-Lite peripheral** on the **Zynq-7000 SoC** using Vivado. The design implements hardware–software co-design by connecting a custom Verilog-based peripheral in the Programmable Logic (PL) with the Processing System (PS).

The processor writes data to AXI registers to control onboard LEDs, illustrating **memory-mapped I/O** and **PS–PL communication**.

---

## Objectives
- Design a custom AXI4-Lite peripheral using Verilog HDL  
- Package the design as a reusable IP using Vivado IP Packager  
- Integrate the custom IP with the Zynq Processing System  
- Implement PS-to-PL communication using memory-mapped registers  
- Verify functionality using a bare-metal C application

---

## Tools & Technologies
- Vivado Design Suite  
- Vitis IDE  
- Verilog HDL  
- Embedded C  
- Zynq-7000 SoC Platform

---

## Hardware Design Flow
1. Create block design in Vivado
2. Add Zynq Processing System
3. Create Custom AXI4-Lite IP using IP Packager
4. Connect AXI Interconnect between PS and Custom IP
5. Assign address space for AXI registers
6. Generate bitstream

---

## Software Design Flow
1. Export hardware to Vitis
2. Create bare-metal application
3. Write data to AXI registers
4. Observe LED output from PL


---

## Key Concepts Demonstrated
- AXI4-Lite Protocol  
- Custom IP Design  
- Memory-Mapped I/O  
- PS–PL Communication  
- FPGA SoC Design Flow  
- Hardware–Software Co-Design

---

## Results
- Custom AXI peripheral successfully integrated with Zynq PS  
- Bitstream generated and implemented without timing violations  
- LED output verified through AXI register write

---

## Applications
- FPGA-based SoC prototyping  
- Embedded hardware accelerator integration  
- Custom peripheral development for ASIC/FPGA workflows

---

## Future Improvements
- Extend design to AXI4-Full or AXI-Stream interface  
- Integrate DMA for high-speed data transfer  
- Interface with custom RISC-V processor core

---

## Author
Ann Mary Roy  
M.Tech VLSI Design & Embedded Systems

---

## Project Structure
