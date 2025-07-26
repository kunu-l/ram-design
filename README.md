# RAM Design

~ Objective:
    Design and simulate a simple *synchronous RAM* module with "read" and "write" operations using Verilog.

~ Files Included:
- "synchronous_ram.v" - 16x8-bit RAM design
- "tb_synchronous_ram.v" - Testbench to verify functionality
- "ram.vcd" - Simulation output for GTKWave
  
~ How to Run:
bash=
iverilog -o ram_test tb_synchronous_ram.v synchronous_ram.v
vvp ram_test
gtkwave ram.vcd
