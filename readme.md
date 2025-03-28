[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vxyPYWbJ)
# 2025 50.002 1D Project

This starter template is created using Alchitry Lab V2, written in LucidV2 language. Full documentation can be found at [Alchitry's official website](https://alchitry.com/tutorials/). 

# Computation-Structure-Lab3

FPGA-based ALU implementation using Lucid on Alchitry, supporting arithmetic, boolean, comparison, and shift operations with FSM-based input handling.

## Features

✅ 32-bit ALU operations  
✅ Boolean logic, arithmetic, comparison, and shifting  
✅ FSM-based input handling  
✅ Implemented using **Lucid HDL** in **Alchitry Labs**  
✅ Auto Tester

## ALU Operations

| Operation   | ALUFN Code | Description |
| ----------- | ---------- | ----------- |
| Addition    | `000000`   | A + B       |
| Subtraction | `000001`   | A - B       |
| MUL         | `000010`   | A & B       |
| AND         | `011000`   | A \| B      |
| OR          | `011110`   | A ^ B       |
| XOR         | `010110`   | A << B      |
| "A"         | `011010`   | A >> B      |
| SHL         | `100000`   | A == B      |
| SHR         | `100001`   | A < B       |
| SRA         | `100011`   | A < B       |
| CMPEQ       | `110011`   | A < B       |
| CMPLT       | `110101`   | A < B       |
| CMPLE       | `110111`   | A < B       |

## Files & Modules

- **alu.luc** – ALU core logic
- **boolean.luc** – Boolean logic operations
- **adder.luc** – Arithmetic operations
- **shift.luc** – Shift operations
- **compare.luc** – Comparison operations
- **alu_manual_tester.luc** – Manual Tester
- **alu_fsm** - Brain of the operation
