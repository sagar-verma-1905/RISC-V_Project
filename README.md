🚀 RISC-V Microprocessor Core Implementation

📖 Project Overview

This repository contains the RTL design and verification files for a 32-bit RISC-V microprocessor core. The project is structured to maintain clean hardware design practices, separating design modules from simulation testbenches.

🗂️ Directory Structure

To maintain consistency across our software tools, this repository strictly tracks source code. Tool-generated logs and waveforms are explicitly ignored.

/rtl - Contains all synthesizable Verilog design files (e.g., ALU, Register File, Control Unit).

/tb - Contains all simulation testbenches used to verify the design modules.

/docs - Architecture diagrams, ISA references, and design documentation.

🛠️ Toolchain

Synthesis & Linting: Yosys

Simulation: Icarus Verilog (iverilog) & GTKWave

Languages: Verilog-2001 / SystemVerilog

🤝 Git Workflow & Commit Rules

To ensure a clean version history, all team members must follow these commit guidelines:

Descriptive Messages: Start commits with an action verb (e.g., Add, Fix, Update, Refactor).

Example: Fix timing issue in the instruction decode pipeline stage

Branching: Do not commit directly to main. Create a feature branch (e.g., feature-alu), push your changes, and open a Pull Request.

No Build Junk: Never force-add .vcd, .log, or .jou files.

👥 Team Members

[Your Name] - Team Lead / Top-Level Integration

[Teammate 1 Name] - [Assigned Module/Role]

[Teammate 2 Name] - [Assigned Module/Role]

[Teammate 3 Name] - [Assigned Module/Role]

Last Updated: [Current Date] - Project initialization and repository setup.
