# 4-Bit Two's Complement Generator Using Verilog HDL

A Digital Logic Design project focused on the implementation of a 4-bit Two’s Complement Generator using Boolean algebra, Karnaugh Map (K-Map) simplification, combinational logic design, and Verilog HDL simulation.

## Project Overview

This project implements a digital circuit capable of generating the two’s complement of a 4-bit binary number. The system accepts four binary input bits:

```text id="0ftjlwm"
A, B, C, D
```

and produces four output bits:

```text id="0o7g7z5"
W, X, Y, Z
```

which represent the corresponding two’s complement value of the input.

The project demonstrates the complete digital design workflow, including truth table generation, logic simplification, hardware circuit implementation, Verilog HDL modeling, and simulation verification.

## Objectives

* Design a functional 4-bit two’s complement generator
* Simplify Boolean expressions using Karnaugh Maps
* Implement combinational logic circuits
* Simulate the design using Verilog HDL
* Verify output correctness through simulation

## Core Concepts

* Boolean Algebra
* Combinational Logic Design
* Karnaugh Map (K-Map) Simplification
* Verilog HDL
* Digital Circuit Simulation

## Simplified Boolean Expressions

### Output W

```text id="nlf8y9"
W = A ⊕ (B + C + D)
```

### Output X

```text id="l7vg6q"
X = B ⊕ (C + D)
```

### Output Y

```text id="trny0l"
Y = C ⊕ D
```

### Output Z

```text id="4aflm6"
Z = D
```

## Project Workflow

1. Constructed the truth table for all input combinations
2. Simplified logic expressions using K-Maps
3. Designed the combinational logic circuit
4. Performed hardware and software simulation
5. Verified outputs with the expected truth table

## Implementation Details

The project includes:

* Truth Table Design
* K-Map Simplification
* Logic Circuit Design
* Hardware Implementation
* Verilog HDL Modeling
* Procedural and Continuous Assign Verilog Simulation
* Output Waveform Verification

## Tools & Technologies

* Verilog HDL
* Quartus Prime
* Digital Logic Design
* Logic Circuit Simulation Tools

## Repository Structure

```text id="e8hpt8"
├── README.md
└── Project_Report.pdf
```

## Contributors

| Name                 | ID            |
| -------------------- | ------------- |
| Md Moon Rahman Nayem | 2022-3-60-210 |
| Md Arafat Hossain    | 2022-1-60-330 |
| Monsurul Hoque Akib  | 2022-1-60-088 |
| Anik Sutrodhar       | 2022-1-60-292 |

## Academic Information

* **Course Title:** Digital Logic Design
* **Course Code:** CSE345
* **Group:** 07
* **Department:** Computer Science and Engineering
* **Institution:** East West University

## Supervisor

**Musharrat Khan**
Senior Lecturer
Department of Computer Science and Engineering
East West University

## Conclusion

This project successfully demonstrates the implementation of a 4-bit two’s complement generator using combinational logic and Verilog HDL. The simulation results validated the correctness of the design, and the project provided practical experience in digital circuit design, logic simplification, and hardware description language based modeling.
