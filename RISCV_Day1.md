
## Day 1: Introduction to RISC-V ISA and GNU Compiler Toolchain

---

### RV-D1SK1 — Introduction to RISC-V Basic Keywords

#### L1 — Introduction

- Introduction to the RISC-V Instruction Set Architecture
- Code Flow:
  - High-Level Languages → Assembly (RISC-V, ARM, x86) → Binary Machine Code (0s and 1s)
- Assembly code is executed using processor designs based on Register Transfer Level (RTL) logic.

---

#### L2 — Software to Hardware Pathway

**Operating System Responsibilities:**

1. Managing Input/Output devices
2. Allocating system memory
3. Executing low-level system functions

---

#### L3 — Course Outline & Instruction Types

**Hands-on C Programming Introduction**

**Classification of Instructions:**

- **Pseudo Instructions** – Simplified commands (not data-handling)
- **RV64I** – Core Integer instructions
- **RV64M** – Extensions for multiplication/division
- **RV64 F/D** – Floating-point operations

**Explored the Application Binary Interface (ABI):** Register usage, stack pointer roles, and memory allocation basics.

---

## RV_D1SK2 — Lab Work: Setting Up & Coding with the RISC-V Toolchain

#### L1 — Writing a Program to Sum Numbers from 1 to N

---

#### L2 — RISC-V GCC Compile and Disassemble

---

#### L3 — Spike Simulation and Debugging

---

## RV-D1SK3 — Integer Number Representation

#### L1: 64-bit Unsigned Numbers

- **Double Word (64-bit):** Range 0 to 2^64 - 1.

---

#### L2: 64-bit Signed Numbers

- **MSB = 0 →** positive; **MSB = 1 →** negative.
- **Two's complement procedure:**
  - Binary representation
  - Invert bits (1's complement)
  - Add 1

---

#### L3: Lab for Signed and Unsigned Numbers
