
## Day 2: Introduction to ABI and Basic Verification Flow

---

### RV-D2SK1 — Application Binary Interface (ABI)

#### L1: Introduction to ABI

The Application Binary Interface (ABI) defines the low-level interface between application code and the underlying hardware or operating system. It specifies:

- Calling conventions (how functions receive parameters and return values)
- Register usage and conventions
- Memory layout and data type sizes

---

#### L2: Memory Allocation for Double Words

- A double word in RISC-V (RV64) architecture refers to 64 bits (8 bytes), which is the standard word size for storing 64-bit integers or addresses in memory.
- Double words must be stored at 8-byte aligned addresses (i.e., addresses divisible by 8) to ensure efficient access and avoid alignment faults on certain architectures.
- During execution, memory for double words may be allocated on the stack (for local variables) or heap (for dynamic allocation), and proper alignment must be preserved by the compiler or programmer.

---

#### L3: Load, Add, and Store Instructions

1. **Load:** `lw x5, 0(x6)` → Load the word from address in `x6` into `x5`
2. **Add:** `add x7, x5, x6` → `x7 = x5 + x6`
3. **Store:** `sw x7, 4(x6)` → Store the value in `x7` to memory address `(x6 + 4)`

**Execution Flow Example:**

```
lw x5, 0(x10)      # Load word at address in x10 to x5
lw x6, 4(x10)      # Load word at address (x10 + 4) to x6
add x7, x5, x6     # Add values in x5 and x6, store result in x7
sw x7, 8(x10)      # Store result from x7 at address (x10 + 8)
```

---

#### L4: Concluding 32 Registers and Their Respective ABI Names

| Register | ABI Name | Usage                       | Saver  |
|:---------|:------------|:-----------------------------|:--------|
| x0       | zero         | Hard-wired zero               | -        |
| x1       | ra           | Return address                | Caller   |
| x2       | sp           | Stack pointer                 | Callee   |
| x3       | gp           | Global pointer                | -        |
| x4       | tp           | Thread pointer                | -        |
| x5–x7    | t0–t2        | Temporaries                   | Caller   |
| x8       | s0/fp        | Saved/frame pointer           | Callee   |
| x9       | s1           | Saved register                | Callee   |
| x10–x11  | a0–a1        | Function args / return values | Caller   |
| x12–x17  | a2–a7        | Function arguments            | Caller   |
| x18–x27  | s2–s11       | Saved registers               | Callee   |
| x28–x31  | t3–t6        | Temporaries                   | Callee   |

---

## RV-D2SK2 — Lab Work: Custom Sum Algorithm in Assembly

#### L1 — Study New Algorithm for Sum 1 to N Using ASM

#### L2 — Review ASM Function Call

#### L3 — Simulate New C Program with Function Call

---

## RV-D2SK3 — Basic Verification Flow using Icarus Verilog

#### L1 — Lab to Run C-Program On RISC-V CPU
