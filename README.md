# CMOS-Full-Adder-Optimization
Transistor-level CMOS full adder design and optimization, focusing on transistor sizing, propagation delay minimization, and circuit performance characterization using Synopsys Custom Compiler and HSPICE.

# CMOS Full Adder Design & Timing Optimization

## Overview

This project focuses on the transistor-level design and optimization of a CMOS full adder, with an emphasis on minimizing propagation delay through transistor sizing.

The full adder is implemented using CMOS transistor logic and evaluated through circuit-level simulations. Different NMOS and PMOS transistor widths are explored to investigate their impact on circuit timing performance and identify an optimized sizing configuration.

The project uses Synopsys Custom Compiler for circuit design and HSPICE for simulation and performance analysis.

## Design Specifications

The full adder performs binary addition of three 1-bit inputs and produces a Sum output and a Carry-out output.

**Inputs:**
- A: First binary input
- B: Second binary input
- Cin: Carry-in

**Outputs:**
- Sum: Sum output
- Cout: Carry-out

### Functional Equations

- Sum = A ⊕ B ⊕ Cin
- Cout = AB + ACin + BCin

## Project Objectives

- Implement a functional CMOS full adder at the transistor level.
- Verify circuit functionality across all eight possible input combinations.
- Investigate the impact of NMOS and PMOS transistor sizing on propagation delay.
- Optimize transistor widths to minimize circuit timing delay.
- Analyze timing characteristics and compare baseline and optimized designs.

## Design & Simulation Tools

| Tool | Application |
|---|---|
| Synopsys Custom Compiler | Schematic capture and transistor-level circuit design |
| HSPICE | Circuit simulation and timing analysis |
| CMOS Technology | NMOS and PMOS transistor implementation |

## Optimization Methodology

Transistor sizing plays an important role in determining CMOS circuit performance. Variations in transistor width affect drive strength, parasitic capacitance, and switching behavior.

The optimization process involves:

1. Establishing an initial transistor sizing configuration.
2. Simulating the full adder using HSPICE.
3. Measuring propagation delays across relevant input-to-output transitions.
4. Sweeping transistor widths to evaluate timing performance.
5. Identifying the sizing configuration that minimizes the selected delay metric.
6. Comparing the optimized design against the baseline implementation.

## Results & Performance Analysis

*Results will be updated upon completion of circuit optimization and simulation.*

| Metric | Baseline | Optimized |
|---|---|---|
| NMOS Width | TBD | TBD |
| PMOS Width | TBD | TBD |
| Propagation Delay | TBD | TBD |
| Transistor Count | TBD | TBD |

### Simulation Results

- Transient response: TBD
- Sum output timing: TBD
- Carry-out timing: TBD
- Optimized transistor sizing: TBD


## Key Learning Outcomes

- Transistor-level CMOS digital circuit design.
- NMOS and PMOS sizing and optimization.
- HSPICE-based circuit simulation and characterization.
- Propagation delay analysis and timing optimization.
- Understanding the tradeoffs between transistor sizing and circuit performance.

## About

Developed as part of the Tufts University undergraduate Electrical Engineering VLSI coursework (EE103), exploring CMOS digital circuit implementation and transistor-level performance optimization.
