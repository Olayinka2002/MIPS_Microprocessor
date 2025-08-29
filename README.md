# MIPS_Microprocessor
32-bit MIPS Microprocessor design in Logisim
# Logisim Microprocessor Design

This repository contains a custom microprocessor designed in **Logisim Evolution**.  
It demonstrates a simple RISC-style CPU with an ALU, control unit, registers, and memory.

## Features
- 8-bit datapath (customizable)
- Basic instruction set: `ADD`, `SUB`, `AND`, `OR`, `JMP`, `LOAD`, `STORE`
- Single-cycle instruction execution
- Separate `ALU`, `Control Unit`, `Register File`, and `Memory` circuits

## Repository Structure
- `circuits/` – Logisim `.circ` files (CPU, ALU, Memory, Control Unit)
- `docs/` – Project documentation (architecture diagrams, ISA, block descriptions)
- `examples/` – Example programs and machine code for testing

## Getting Started
1. Install [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution).
2. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/microprocessor-logisim.git
   cd microprocessor-logisim

