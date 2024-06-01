# Project 0:
Test submission

# Project 1 -> Boolean Functions and Gate Logic
Introduction to HDL and 15 elementary logic gates implementation:
### .hdl
- Not, Not16, 
- And, And16, 
- Or, Or16, Or8Way, Xor
- Mux, Mux16, Mux4Way16, Mux8Way16, 
- DMux, DMux4Way, DMux8Way, 

# Project 2 -> Boolean Arithmetic and the ALU
Implement a family of adders, and most importantly - the ALU (Arithmetic Logical Unit):
### .hdl
- HalfAdder, FullAdder
- Add16, Inc16
- ALU

# Project 3 -> Memory
Building the computer's main memory unit (RAM):
### .hdl
> a:
- Bit, Register
- RAM8, RAM64
- PC (Program Counter)

> b:
- RAM512, RAM4K, RAM16K

# Project 4 -> Machine Language
Writing low-level programs using the Hack machine language:
### .asm
- fill: Fill screen with black pixels on keyboard press, flush on release.
- mult: Based on repetitive addition, multiply 2 register's state, and store the results in a third one.

# Project 5 -> Computer Architecture
Assemble all previously built building blocks into a general-purpose 16-bit computer called Hack.
Build Hack Central Processing Unit (CPU).
Integrate the CPU with the RAM, creating a full-blown computer system capable of executing programs written in the Hack machine language.
### .hdl
- CPU: The Hack Central Processing unit (CPU).
- Memory: The complete address space of the Hack computer's memory, including RAM and memory-mapped I/O. 
- Computer: The Hack computer, consisting of CPU, ROM and RAM.

# Project 6 -> Assembler
Build an assembler; we'll develop the capability of translating symbolic Hack programs into binary code that can be executed as-is on the Hack platform.
### .cpp
- HACK-Assembler-XYZ: My implementation of the Hack Assembler in C++ (I will probably improve it every so often)
