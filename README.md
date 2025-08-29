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
- `Full_Adder`. This was the first design in the project
- `ALU Design  ` Then the one, four and eventually 32 bit alu design followed
- `Register` Next was the 1, 4 and 32 bit register design
- `Opcode`Next, the logic for the opcode along with the program counter design
- `Full_Microprocessor_Design` Lastly was implementing all the other module to create our single cycle processor.

## Getting Started
1. Install [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution).
2. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/microprocessor-logisim.git
   cd microprocessor-logisim

