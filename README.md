# Jaishyam Reddy Reddivari

**Design Verification Engineer | MS Computer Engineering, Syracuse University**

Built four independent UVM verification environments from scratch — AXI4 slave IP, RV32I pipelined processor, asynchronous CDC FIFO, and UART 16550 controller. Developed constrained-random testbenches, reference-model scoreboards, SVA assertion suites, and Python multi-seed regression infrastructure. Debugged 50+ RTL and testbench defects through waveform root-cause analysis across all projects.

---

### Featured Projects

**[AXI4 Slave UVM Verification](https://github.com/JaishyamReddivari/AXI_RAM_Verification)** — Black-box verification of AXI4 slave RAM against ARM AMBA spec. Byte-addressable associative-array scoreboard, 14 SVA assertions, 22 directed + constrained-random tests. **97.5% functional coverage, 0 mismatches across 2500 seeds.**

**[RISC-V 5-Stage Pipelined Processor](https://github.com/JaishyamReddivari/RISC-V-Design-UVM-Verification)** — Designed RV32I core with forwarding and hazard detection, then verified it with a full UVM environment: dual agents, ISA reference-model scoreboard, pipeline monitors. 28 SVA assertions, 19 covergroups, coverage driven from 52% → 96%. Found a register-file bypass bug causing stale reads.

**[Asynchronous CDC FIFO](https://github.com/JaishyamReddivari/CDC_FIFO)** — 16-deep async FIFO with Gray-coded pointers, dual-clock domains, and 2-FF synchronizers. UVM environment with dual-clock monitors and FIFO-queue reference scoreboard. 500-transaction regression at asymmetric clock ratios, 0 mismatches.

**[UART 16550 Controller](https://github.com/JaishyamReddivari/UART-16550-Controller)** — RTL design based on PC16550D spec with TX/RX state machines, programmable baud-rate generator, and FIFO buffering. UVM environment with serial loopback and mailbox scoreboard. Resolved 17 RTL bugs and 13 testbench defects.

---

### Technical Skills

`SystemVerilog` · `UVM 1.2` · `SVA` · `Verilog` · `Python` · `C++` · `Shell/Bash`
`AXI4` · `AHB` · `APB` · `Wishbone` · `UART` · `SPI` · `I2C`
`Questa/ModelSim` · `Riviera-PRO` · `Vivado` · `MATLAB`

---

### Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jaishyam--reddy--reddivari-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/jaishyam-reddy-reddivari/)
[![Email](https://img.shields.io/badge/Email-jaishyamreddivari%40gmail.com-EA4335?style=flat&logo=gmail)](mailto:jaishyamreddivari@gmail.com)
