
# RISCV Day 3 - Digital Logic with TL-Verilog and Makerchip

---

## RISCV-D3SK1 - Combinational Logic in TL-Verilog using Makerchip

### L1_Introduction to Logic Gates

1. **Logic Gates**

2. **Combinational Circuits**

3. **Boolean Operators**
   - Connect logical expressions in both hardware and software design.

---

### L2_Basic Mux Implementation and Introduction to Makerchip

- A MUX (Multiplexer) selects one of multiple inputs to produce one output based on control signals.
- **Verilog Syntax**: `assign f = s ? X1 : X2;`

---

### L3_Labs for Combinational Logic

#### Example: Pythagoras Theorem

#### Example: Logic Gates

#### Example: Combinational Calculator
- Building a simple calculator supporting `+`, `-`, `*`, `/` in pure combinational logic.

---

## RISCV-D3SK2 – Sequential Logic

### L1_Introduction to Sequential Logic and Counter Lab
- Sequential elements (like flip-flops) capture state on clock edges.

#### Example: Fibonacci Series Lab

#### Example: Counter

---

### L2_Sequential Calculator Lab

---

## RISCV-D3SK3 - Pipelined Logic

### L1_Pipelined Logic and Re-Timing
- Pipeline logic refers to the structured approach of breaking down a process into sequential stages.
- Each stage processes data and passes it to the next.
- This technique improves efficiency and throughput.

### L2_Pipeline Logic Advantages and Demo in Platform

### L3_Lab on Error Conditions within Computation Pipeline

### L4_Lab on 2-Cycle Calculator

---

## RISCV-D3SK4 – Validity

### L1_Introduction to Validity and Its Advantages

### L2_Lab on Validity and Valid-When Condition
- Add validity flags to the two-cycle calculator and observe transaction validity.

### L3_Lab to Compute Total Distance

### L4_Lab on 2-Cycle Calculator with Validity
- Combine pipeline and validity to build a robust staged calculator.

### L5_Calculator Single Value Memory Lab
- Add a memory element to store and recall a single value within the pipeline.

---

## RISCV Day 3 Wrap-up

### L1_Introduction to Hierarchy Concept (Bonus)
