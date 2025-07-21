# 8-bit Kogge-Stone BLC Adder

<img width="360" alt="image" src="https://github.com/user-attachments/assets/e88df524-e8c9-485e-aae0-1dfafa9d9282" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/7968b487-6265-4722-9907-e80d39c9c549" />



This repository contains the final report of a university project for UNIBO Master's degree in Electronics. It is focused on the design, simulation, and characterization of a digital adder based on a modified Kogge-Stone architecture with BLC optimization.

## Overview

The project was developed using **Cadence Virtuoso** and aimed to optimize **latency** in digital addition circuits, comparing trade-offs with area and power consumption. The adder operates on 8-bit inputs and supports both addition and subtraction operations.

## Functional Blocks
  - XOR blocks for sum/subtract logic
  - “Single-bit” blocks for generate/propagate signal generation
  - O-operator blocks with buffering logic for timing balance
  - Registers for synchronous operation

## Results

- Static Power Consumption: ~20.9 nW
- Energy per Clock Cycle: ranges from ~98 fJ to ~349 fJ depending on activity level
- Area Growth: proportional to _N × log₂N_
- Performance: significantly lower latency compared to other carry-lookahead adders (e.g. Carry Bypass, Carry Select)

## Report

The full project report is available here: [kogge-stone-BLC-8bit.pdf](kogge-stone-BLC-8bit.pdf)

