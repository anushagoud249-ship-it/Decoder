# 3-to-8 Decoder using Verilog

## Project Description

This project implements a **3-to-8 Decoder** using Verilog HDL. A decoder is a combinational logic circuit that converts an n-bit binary input into one of 2ⁿ output lines. For a 3-bit input, exactly one of the eight outputs becomes HIGH while the remaining outputs stay LOW.

The project includes:
- Verilog source code
- Testbench for functional verification
- Simulation results
- Waveform output

## Truth Table

| Input | Output |
|-------|----------------|
|000|00000001|
|001|00000010|
|010|00000100|
|011|00001000|
|100|00010000|
|101|00100000|
|110|01000000|
|111|10000000|

## Files

- decoder.v – Verilog implementation
- decoder_tb.v – Testbench
- simulation_output.txt – Console output
- simulation.png – Waveform screenshot

## Software Requirements

- Icarus Verilog
- GTKWave
- ModelSim (optional)
- Vivado (optional)

## Compilation

```bash
iverilog -o decoder decoder.v decoder_tb.v
```

## Run Simulation

```bash
vvp decoder
```

## View Waveform

```bash
gtkwave decoder.vcd
```

## Applications

- Memory Address Decoding
- Instruction Decoding
- Digital Communication Systems
- Embedded Systems

## Author
