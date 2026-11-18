# Verilog HDL Study

## Overview

This repository documents my study of Verilog HDL, digital logic design, and RTL development.

The goal is to build a strong foundation in hardware design through Verilog implementations, testbench development, simulation, and waveform analysis.

## Design and Verification Workflow

1. Write the RTL design (`.v`).
2. Develop a testbench (`_tb.v`).
3. Compile and simulate using Icarus Verilog.
4. Generate VCD waveform files.
5. Analyze simulation results using GTKWave.

## Current Repository

- `01_verilog_basics/` — Introductory Verilog HDL exercises

## Learning Roadmap

### Phase 1 — Basic Logic Gates
- AND, OR, NAND, NOR, NOT, XOR
- Multi-input logic gates
- Half Adder and Full Adder
- Half Subtractor and Full Subtractor

### Phase 2 — Combinational Logic
- Multiplexers and Demultiplexers
- Decoders and Encoders
- Priority Encoder
- Comparator
- 4-bit Ripple Carry Adder
- 4-bit Adder/Subtractor
- 4-bit ALU

### Phase 3 — Sequential Logic
- Latches and Flip-Flops
- Registers and Shift Registers
- Counters
- Clock and Reset Design

### Phase 4 — FSM and Memory
- Moore and Mealy FSMs
- FSM-Based Controllers
- Register Files
- RAM and Block RAM

### Phase 5 — Datapath Design
- ALU Integration
- Register File Integration
- Multiplexer-Based Data Routing
- FSM-Controlled ALU Datapath

### Phase 6 — Tiny CPU Design
- Instruction Execution
- Program Counter
- Control Unit
- Datapath Integration
- Memory Read and Write
- CPU Testbench and Functional Verification

### Phase 7 — FPGA Implementation
- Vivado Synthesis
- Implementation and Timing Analysis
- Bitstream Generation
- FPGA Board Verification
- LED, UART, and ILA-Based Debugging

### Advanced Topics
- Pipelining
- Data Hazards and Forwarding
- Cache and Bus Interfaces
- Advanced CPU Architecture

## Additional Simulation Studies

### CMOS Inverter Characteristics
- 74HC04 Inverter Behavioral Modeling
- 74HC14 Schmitt-Trigger Behavioral Modeling
- Switching Threshold and Hysteresis Comparison
- Propagation Delay Simulation
- Multi-Stage Inverter Chain Analysis

These simulations use simplified behavioral models rather than transistor-level circuit models.

## Development Environment

- **Language:** Verilog HDL
- **Editor:** Visual Studio Code
- **Simulator:** Icarus Verilog
- **Waveform Viewer:** GTKWave
- **FPGA Tools (Planned):** Xilinx Vivado

## Project Status

This repository is an ongoing learning project. The roadmap describes planned study topics and does not imply that every module has been implemented or verified.
