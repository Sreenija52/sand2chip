# RISC-V based SOC Tapeout program VSD

## Project overview
This project is my journey into the world of chip design — building a RISC-V based System-on-Chip (SoC) from scratch and taking it all the way to tapeout.

It covers from RTL design, synthesis, floorplanning, place-and-route(physical design) and finally GDSII generation. Think of it as turning lines of Verilog into a chip you can actually fabricate!

The repo holds my RTL code, testbenches, synthesis, PnR scripts and documentation capturing not just the flow but also the learning experience of being part of a real tapeout program with VSD.

## Key features
- RISC-V RV32I core integration (custom or open-source core)
- AXI/APB interconnect for peripherals
- Power/clock planning and floorplanning for tapeout
- Timing closure and static timing analysis
- Testbench for RTL functional verification (UVM/SystemVerilog or simple testbenches)
- Scripts for synthesis (Yosys/Genus), place-and-route (OpenROAD/Innovus) and GDSII generation


## 📅 Week 0 — Setup & Tools

| Task | Description | Status |
|------|-------------|---------|
| [**Task 0**](images/README_Day0.md) | 🛠️ [Tools Installation](images/README_Day0.md) — Installed **Iverilog**, **Yosys**, and **gtkWave** | ✅ Done |

### 🌟 Key Learnings from Week 0
- Installed and verified **open-source EDA tools** successfully.  
- Learned about **basic environment setup** for RTL design and synthesis.  
- Prepared the system for upcoming **RTL → GDSII flow experiments**.
