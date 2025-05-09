
# RISCV Day 3 - Digital Logic with TL-Verilog and Makerchip

## RISCV-D3SK1 - Combinational Logic in TL-Verilog using Makerchip

### L1_Introduction to Logic Gates

1. **Logic Gates**

![Screenshot 2025-05-09 163350](https://github.com/user-attachments/assets/dcf89371-27c9-4080-be33-66d1ea55d5a7)

2. **Combinational Circuits**

![Screenshot 2025-05-09 163653](https://github.com/user-attachments/assets/5c58235c-2f48-49f0-b93c-b22447a27356)

3. **Boolean Operators**

![Picture1](https://github.com/user-attachments/assets/b9b63e69-4218-47a7-be4c-8603fa38c19e)

### L2_Basic Mux Implementation and Introduction to Makerchip

- A MUX (Multiplexer) selects one of multiple inputs to produce one output based on control signals.
- **Verilog Syntax**: `assign f = s ? X1 : X2;`

![Picture1](https://github.com/user-attachments/assets/31ee07a6-cd20-44f3-a50d-4874eb172894)


### L3_Labs for Combinational Logic

#### Example: Pythagoras Theorem

![Picture2](https://github.com/user-attachments/assets/2d2c47a0-cdb7-4075-88bb-78a9db2fbb71)


#### Example: Logic Gates

![Picture3](https://github.com/user-attachments/assets/bc5f430f-5054-46cc-9009-d06ee110fcc4)


#### Example: Combinational Calculator
- Building a simple calculator supporting `+`, `-`, `*`, `/` in pure combinational logic.

![Picture4](https://github.com/user-attachments/assets/61e10c69-0062-4be9-a5cd-f926dcbd0813)


## RISCV-D3SK2 – Sequential Logic

### L1_Introduction to Sequential Logic and Counter Lab
- Sequential elements (like flip-flops) capture state on clock edges.

#### Example: Fibonacci Series Lab

![Picture5](https://github.com/user-attachments/assets/7f1fd6e0-0539-42a5-b6ba-a1108820ecbd)


#### Example: Counter

![Picture6](https://github.com/user-attachments/assets/4f1340f0-2010-4192-9cb8-8a7075767bbf)


### L2_Sequential Calculator Lab

![Picture7](https://github.com/user-attachments/assets/bfd363e1-137b-4c8f-a013-964525c32be7)

![Picture8](https://github.com/user-attachments/assets/61c7a745-da31-45af-aaf4-1c7964125ec9)

## RISCV-D3SK3 - Pipelined Logic

### L1_Pipelined Logic and Re-Timing
- Pipeline logic refers to the structured approach of breaking down a process into sequential stages.
- Each stage processes data and passes it to the next.
- This technique improves efficiency and throughput.

### L2_Pipeline Logic Advantages and Demo in Platform

![Picture9](https://github.com/user-attachments/assets/605a4d91-2d03-4745-8bc4-5a4e1c45fe69)


### L3_Lab on Error Conditions within Computation Pipeline

![Picture10](https://github.com/user-attachments/assets/5f31b351-edb6-4fc2-aeda-e1302d06e501)

### L4_Lab on 2-Cycle Calculator

![Picture11](https://github.com/user-attachments/assets/124399c7-cca2-4578-8434-71a1a1cf8ffc)

## RISCV-D3SK4 – Validity

### L1_Introduction to Validity and Its Advantages

### L2_Lab on Validity and Valid-When Condition
- Add validity flags to the two-cycle calculator and observe transaction validity.

![Picture12](https://github.com/user-attachments/assets/c7bb14be-3b6a-4feb-b860-7d6a667789e1)

### L3_Lab to Compute Total Distance

![Picture13](https://github.com/user-attachments/assets/03e1d8ff-6066-4118-bd78-c945c539d8ff)

### L4_Lab on 2-Cycle Calculator with Validity
- Combine pipeline and validity to build a robust staged calculator.

![Picture14](https://github.com/user-attachments/assets/6d874296-22ea-4717-af9d-8e08cd88efb6)

### L5_Calculator Single Value Memory Lab
- Add a memory element to store and recall a single value within the pipeline.

![Picture15](https://github.com/user-attachments/assets/20878278-fcec-4d68-811a-f64ec5da0dd0)

## RISCV Day 3 Wrap-up

### L1_Introduction to Hierarchy Concept

![Picture16](https://github.com/user-attachments/assets/5751f2f8-53c1-4530-9f9a-f3708f68baf9)
