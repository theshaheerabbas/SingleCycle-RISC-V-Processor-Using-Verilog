# SingleCycle-RISC-V-Processor-Using-Verilog
This repository contains an implementation of a RISC-V processor in Verilog. The RISC-V processor is a simplified implementation based on the RISC-V instruction set architecture (ISA). It supports a subset of the RISC-V instructions and provides a basic pipeline architecture.

## Features
Supports a subset of RISC-V instructions. Basic pipeline architecture with stages for instruction fetch, instruction decode, execution, memory access, and write-back. Single-cycle execution for most instructions. Implements a program counter (PC) module for instruction fetching. Implements register files for storing and accessing register values. Implements an ALU (Arithmetic Logic Unit) for executing arithmetic and logical operations. Supports immediate generation for instructions that involve immediate values. Includes a testbench module for functional verification.

## Getting Started
To get started with the RISC-V processor, follow these steps:

Clone the repository: git clone https://github.com/theshaheerabbas/SingleCycle-RISC-V-Processor-Using-Verilog.git Navigate to the project directory: cd risc-v-processor Open the project in your preferred Verilog development environment (e.g., Quartus, Vivado, etc.). Explore the source files to understand the implementation details of the processor. Modify or extend the processor as per your requirements. Use the provided testbench module to verify the correctness of the processor implementation. Simulate and test the processor using various assembly programs. Share your feedback, suggestions, or bug reports by creating an issue in the repository.

## Contributing
Contributions to the RISC-V processor project are welcome! If you find any bugs, want to add new features, or improve the existing implementation, please feel free to create a pull request. Make sure to follow the coding style guidelines and provide a clear description of your changes.

References Here are some references and resources that might be helpful in understanding RISC-V and processor design:

RISC-V Instruction Set Manual: https://riscv.org/specifications/ Computer Organization and Design by David A. Patterson and John L. Hennessy Digital Design and Computer Architecture by David Money Harris and Sarah L. Harris Online forums and communities: https://riscv.org/community/ Please refer to the references for a deeper understanding of the RISC-V architecture and processor design concepts.
