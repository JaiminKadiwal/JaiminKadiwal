# Jaimin Kadiwal

MS ECE student at Johns Hopkins (graduating 2027). I design and verify digital hardware: SystemVerilog RTL,
constrained-random verification with cocotb, and formal proofs with SymbiYosys.
Looking for Summer 2027 internships in RTL design, design verification and FPGA engineering.

## Projects

- **[tensor-mac](https://github.com/JaiminKadiwal/tensor-mac)**: parameterized INT8 systolic-array matrix-multiply
  accelerator. Matches NumPy on 500 random tiles with 0 mismatches at N=2 and N=3, an unbounded formal proof
  shows the accumulator never overflows, and mutation testing shows the tests catch real bugs.
- **[verified-rtl-blocks](https://github.com/JaiminKadiwal/verified-rtl-blocks)**: FIFO, skid buffer, round-robin
  arbiter and more, each lint clean, checked by 7,500+ constrained-random cocotb transactions, and formally
  proven (no overflow, no starvation).
- **Keyword spotting on an FPGA**: int8 neural net in VHDL on an Artix-7, bit exact with the Python model on
  128/128 vectors in simulation and on hardware.
- **RTL to GDSII**: 8-bit RISC CPU taken through Cadence Genus synthesis and Innovus place and route in 45 nm.
- **Radiation-hardened SRAM (2024)**: 13-transistor SEU-tolerant cell in 45 nm, read SNM +33% over a published
  16T cell.

**Tools:** SystemVerilog, VHDL, Verilator, Icarus, cocotb, SymbiYosys + z3, Yosys, Vivado,
Cadence Genus / Innovus / Xcelium, Python, C++.
