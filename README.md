# 2:1 Multiplexer in Verilog HDL

## Project Overview
This project implements a basic 2:1 Multiplexer (MUX) using Verilog HDL. It is a beginner-level RTL design project created as part of my transition into VLSI and Digital Design.

## Functionality
A 2:1 MUX selects one of two input signals based on the select line.

- If `sel = 0`, output `y = a`
- If `sel = 1`, output `y = b`

## Design File
- `mux2to1.v` → Verilog RTL design for 2:1 MUX

## Testbench File
- `mux2to1_tb.v` → Testbench used to simulate and verify the MUX behavior

## Truth Table

| sel | a | b | y |
|-----|---|---|---|
| 0   | 0 | 1 | 0 |
| 1   | 0 | 1 | 1 |
| 0   | 1 | 0 | 1 |
| 1   | 1 | 0 | 0 |

## Skills Demonstrated
- Verilog HDL
- Combinational Logic Design
- RTL Design
- Testbench Creation
- Basic Functional Verification

## Learning Outcome
This project helped me understand:
- Verilog module structure
- Input/output declaration
- `assign` statements



## Simulation Result

The design was simulated successfully in EDA Playground using Icarus Verilog.

- Ternary operator (`?:`)
- Basic simulation with a testbench
