# 8:1 Demultiplexer (DEMUX) Verilog Project

## Project Overview
This project demonstrates an **8:1 Demultiplexer (DEMUX)** implemented in Verilog. A demultiplexer routes a single input to one of eight outputs based on a 3-bit select line.

**Learning Outcomes:**
- Conditional routing in Verilog
- Understanding 3-bit select lines
- Module reuse in larger digital designs

## Circuit Description
- **Input:**
  - `d` : Single data input
  - `sel[2:0]` : 3-bit select line to choose the output
- **Outputs:**
  - `y[7:0]` : 8 output lines, only one active at a time

**Truth Table:**

| sel   | Output (y7 y6 y5 y4 y3 y2 y1 y0) |
|-------|---------------------------------|
| 000   | 00000001                        |
| 001   | 00000010                        |
| 010   | 00000100                        |
| 011   | 00001000                        |
| 100   | 00010000                        |
| 101   | 00100000                        |
| 110   | 01000000                        |
| 111   | 10000000                        |

## Files Included
- `txt file ` : 8:1 Demultiplexer module and testbench

## Simulation
The testbench cycles through all select lines and prints which output line is active.  
Run the simulation in **EDA Playground** or any Verilog simulator.

**Example Output:**
sel=000, y=00000001
sel=001, y=00000010
sel=010, y=00000100
sel=011, y=00001000
sel=100, y=00010000
sel=101, y=00100000
sel=110, y=01000000
sel=111, y=10000000

## How to Run
1. Open txt file for code and testbench in a Verilog simulator or EDA Playground.
2. Run the simulation.
3. Observe the console output to verify correct demultiplexer behavior.


