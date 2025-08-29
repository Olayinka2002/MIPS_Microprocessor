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

## Repository Structure(Each folder include the design along with test results)
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
3. For any of the .circ files, open and test the vector files
4. For the main CPU design, the ROM file is filled with specific instruction that are executed sequentially
    - at 0x00000000  NOP
    - at 0x00000004  lw $t0 0(zero)
    - at 0x00000008 lw $t1, 1($zero)
    - at 0x0000000C beq $to, $t1, 3
    - at 0x00000010 add $t0, $t0 $to
    - at 0x00000014 sw $sw $t0, 0($zero)
    - at 0x00000018 j 0x00000000
    - at 0x0000001C add $t2, $t0, $t1
    - at 0x00000020 sw $t2, 2 ($zero)
6. Toggle clk to see the expected results

## 🛠 Skills Demonstrated
- Digital design using Logisim Evolution
- CPU architecture and datapath design
- Instruction Set Architecture (ISA) implementation
- Hardware debugging and test vector creation
- Understanding of single-cycle processor operation

