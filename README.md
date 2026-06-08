# Jaishyam Reddy Reddivari

**Design Verification Engineer | MS Computer Engineering, Syracuse University**

Design Verification engineer building production-style UVM environments from scratch and driving them to coverage closure. Most recent work: a full UVM environment for an 8×8 INT8 systolic-array ML accelerator, taken to 100% functional coverage on the open-source Verilator toolchain. Across five independent projects I've built constrained-random testbenches, reference-model scoreboards, SVA assertion suites, functional-coverage models, and Python multi-seed regression infrastructure, debugging 50+ RTL and testbench defects through waveform root-cause analysis.

---

### Featured Projects

**[8×8 INT8 Systolic-Array Accelerator — UVM Verification](https://github.com/JaishyamReddivari/systolic_array_dv)** — Full UVM verification of a weight-stationary INT8 matrix-multiply accelerator (the compute core of ML accelerators), closed on an open-source Verilator + UVM flow. Constrained-random AXI4-Stream/AXI4-Lite stimulus, a self-checking scoreboard cross-validated against three independent reference models (NumPy, cycle-accurate, C++), and a hand-built functional-coverage model. **100% functional coverage, 97.1% line coverage, 0 failures across 500 regression runs.**

**[AXI4 Slave UVM Verification](https://github.com/JaishyamReddivari/AXI_RAM_Verification)** — Black-box verification of AXI4 slave RAM against ARM AMBA spec. Byte-addressable associative-array scoreboard, 14 SVA assertions, 22 directed + constrained-random tests. **97.5% functional coverage, 0 mismatches.**

**[RISC-V 5-Stage Pipelined Processor](https://github.com/JaishyamReddivari/RISC-V-Design-UVM-Verification)** — Designed RV32I core with forwarding and hazard detection, then verified it with a full UVM environment: dual agents, ISA reference-model scoreboard, pipeline monitors. **28 SVA assertions, 19 covergroups, coverage driven from 52% → 96%.** Found a register-file bypass bug causing stale reads.

**[Asynchronous CDC FIFO](https://github.com/JaishyamReddivari/CDC_FIFO)** — 16-deep async FIFO with Gray-coded pointers, dual-clock domains, and 2-FF synchronizers. UVM environment with dual-clock monitors and FIFO-queue reference scoreboard. **500-transaction regression at asymmetric clock ratios, 0 mismatches.**

**[UART 16550 Controller](https://github.com/JaishyamReddivari/UART-16550-Controller)** —  PC16550D-compliant RTL (TX/RX state machines, programmable baud generator, FIFO buffering) verified with a full UVM environment: serial loopback, dual-path monitors, and a mailbox scoreboard over 500 constrained-random frames. Adds a UVM RAL model with dual address maps for DLAB aliasing, a custom adapter/predictor, and read-back verification. **0 errors across 500 frames; 17 RTL and 16 testbench/RAL bugs resolved.**

---

### Technical Skills

`SystemVerilog` · `UVM 1.2` · `SVA` · `Verilog` · `Python` · `C++` · `Shell/Bash`
`AXI4` · `AHB` · `APB` · `Wishbone` · `UART` · `SPI` · `I2C`
`Questa/ModelSim` · `Riviera-PRO` · `Verilator` · `Vivado` · `MATLAB`

---

### Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jaishyam--reddy--reddivari-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/jaishyam-reddy-reddivari/)
[![Email](https://img.shields.io/badge/Email-jaishyamreddivari%40gmail.com-EA4335?style=flat&logo=gmail)](mailto:jaishyamreddivari@gmail.com)
