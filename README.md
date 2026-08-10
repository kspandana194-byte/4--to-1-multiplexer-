# 4--to-1-multiplexer-
4-to-1 Multiplexer Using Verilog

Description

A 4-to-1 Multiplexer (MUX) is a digital circuit that selects one of four input signals and sends the selected input to a single output.

It uses two select lines to choose one of the four inputs.

Inputs and Outputs

- Inputs: "I0, I1, I2, I3"
- Select lines: "S1, S0"
- Output: "Y"

Truth Table

S1| S0| Output Y
0| 0| I0
0| 1| I1
1| 0| I2
1| 1| I3

Files

- "mux4to1.v" – Verilog design code
- "mux4to1_tb.v" – Testbench for verification
- "simulation/" – Simulation results

Working

The two select lines determine which input is connected to the output.

For example:

- "S1S0 = 00" → "Y = I0"
- "S1S0 = 01" → "Y = I1"
- "S1S0 = 10" → "Y = I2"
- "S1S0 = 11" → "Y = I3"

Tools

- Verilog HDL
- Icarus Verilog / ModelSim / Vivado
- GTKWave (for waveform viewing)

Conclusion

The 4-to-1 Multiplexer successfully selects one of four input signals based on the two select lines and produces the selected signal at the output.
author 
Spandana 
