##SAP-1 Architecture
A comprehensive implementation and simulation of the SAP-1 (Simple-As-Possible) architecture, designed to provide insights into the fundamental operations of a basic computer system. This repository serves as an educational tool for understanding how a basic microprocessor functions, focusing on key components like registers, memory, ALU, and the control unit.
![1](https://github.com/user-attachments/assets/92b65af7-9759-4eb6-9826-3500b6eab6a8)


#Overview
The SAP-1 architecture is a foundational digital computer model introduced by Malvino in "Digital Computer Electronics." It is an entry-level design that helps students and enthusiasts understand the core principles of computer organization and architecture.

#Key Features:
8-bit data bus: Supports basic 8-bit operations.
16-byte memory: Small memory space for educational simplicity.
4-bit instruction set: Minimal instruction set to execute essential tasks.
Registers: Accumulator (A register), B register.
Control unit: Manages instruction decoding and execution.
Arithmetic Logic Unit (ALU): Performs addition and subtraction operations.
Instruction Cycle: Fetch, Decode, and Execute phases.
Components
#Registers:

A Register: Holds the result of ALU operations.
B Register: Stores data for ALU operations.
Program Counter (PC): Points to the next instruction in memory.
Instruction Register (IR): Temporarily stores the current instruction.
Memory:

A 4-bit address space supporting up to 16 memory locations.
#ALU:

Handles basic arithmetic operations (addition, subtraction).
Control Unit:

Generates timing and control signals for coordinating operations.
#Bus System:

A single shared bus for data transfer between components.
Instruction Set:

LDA: Load data into the accumulator.
ADD: Add data to the accumulator.
SUB: Subtract data from the accumulator.
OUT: Output data.
HLT: Halt the system.
Features of This Repository
#Detailed Implementation:
Simulated using Logisim
#Documentation:
Block diagrams and flowcharts for understanding component interactions.
Step-by-step explanation of the instruction execution process.
Test Cases:
Sample programs to demonstrate SAP-1 functionality (e.g., addition, subtraction).
Interactive Simulation:
A user-friendly interface to run SAP-1 instructions interactively
