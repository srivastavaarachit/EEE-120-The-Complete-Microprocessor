# EEE 120: THE COMPLETE MICROPROCESSOR
# LAB 4 - DIGITAL LOGIC & MICROPROCESSOR DESIGN

**Author:** Rachit Srivastava  
**Course:** EEE 120  
**Instructor:** Steven Millman  
**Semester:** Spring 2025  


---

## PROJECT OVERVIEW

This repository contains the complete design and simulation files for Lab 4: "The Complete Microprocessor". The objective of this project was to design, build, and simulate a functioning microprocessor from the ground up using **Digital** for schematic capture and **Verilog** for hardware description language simulation.

The project progresses through the construction of the Memory Address Generation circuit, the Controller, and the final Datapath integration, culminating in a fully simulated CPU capable of executing a custom instruction set.

---

## REPOSITORY MANIFEST

The following file structure represents the complete microprocessor architecture:

```text
.
├── CIRCUIT DESIGNS (.dig)
│   ├── microprocessor.dig        # [Task 4-3] The complete integrated CPU
│   ├── controller.dig            # [Task 4-2] Control logic (IR, Step Reg, ROM)
│   ├── addr_gen.dig              # [Task 4-1] Memory Address Generation
│   ├── alu.dig                   # Arithmetic Logic Unit
│   ├── brainless.dig             # Core logic component
│   ├── program_ctr.dig           # Program Counter
│   ├── program_ram.dig           # RAM module
│   ├── four_bit_reg.dig          # 4-bit Register
│   ├── two_bit_reg.dig           # 2-bit Register
│   ├── four_bit_mux.dig          # 4-bit Multiplexer
│   ├── two_bit_mux.dig           # 2-bit Multiplexer
│   ├── two_bit_bus_mux.dig       # 2-bit Bus Multiplexer
│   ├── four_bit_adder.dig        # 4-bit Adder
│   ├── full_adder.dig            # Full Adder
│   ├── half_adder.dig            # Half Adder
│   ├── incrementer.dig           # Incrementer logic
│   ├── not_neg.dig               # Negation logic
│   └── and_add.dig               # AND/ADD logic
│
├── VERILOG SIMULATION (.v / .vcd)
│   ├── micro_top.v               # Top-level module for simulation
│   ├── microprocessor.v          # Verilog export of the CPU
│   ├── micro_stim.v              # Stimulus file for testing
│   ├── micro_waves.vcd           # Value Change Dump (Waveform data)
│   └── microwavesgtk.gtkw        # GTKWave save file configuration
│
├── MEMORY FILES (.hex / .txt)
│   ├── rom_vals.hex              # Microcode ROM values (Control store)
│   ├── ram_vals.hex              # Program memory (Machine code)
│   └── ram_vals.txt              # Text definition of RAM program
│
└── DOCUMENTATION
    └── thecompletemicroprocessor.pdf  # Lab Report
