# Booth Multiplier in Verilog

## Overview
This project implements a Booth Multiplier using Verilog HDL for efficient signed binary multiplication using Booth’s Algorithm.

## Features
- Supports signed multiplication (2’s complement)
- Reduces number of addition/subtraction operations
- Efficient handling of negative numbers
- Sequential multiplication using shifting

## Algorithm Used
Booth’s Algorithm works by:
- Encoding multiplier bits
- Performing conditional addition/subtraction
- Applying arithmetic right shifts
- Reducing redundant operations

## Design Details
- Input: Signed binary numbers (multiplicand & multiplier)
- Output: Product (2n-bit result)
- Uses registers and control logic for iterative computation

## Files
- `booth_multiplier.v` → Main module
- `booth_multiplier_tb.v` → Testbench

## Simulation
- Tested using Vivado simulator
- Verified for:
  - Positive × Positive
  - Positive × Negative
  - Negative × Negative

## How to Run
1. Open Vivado
2. Add source and testbench files
3. Run behavioral simulation
4. Observe waveform outputs

## Key Learning
- Efficient hardware multiplication techniques
- Handling signed arithmetic in digital systems
- Optimization using Booth encoding

## Author
Bharadwaj