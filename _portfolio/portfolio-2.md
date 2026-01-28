---
title: "16-bit CPU Design and Implementation"
collection: portfolio
permalink: /portfolio/16-bit-cpu/
excerpt: "Designed and implemented a custom 16-bit CPU using SystemVerilog and FPGA-based verification, including a function unit, datapath, control logic, and instruction execution."
---

## Project Overview

This project involved the design, implementation, and verification of a custom 16-bit CPU using SystemVerilog and FPGA-based simulation tools. The processor architecture includes a function unit, arithmetic and logic blocks, a bus system, control logic, and instruction memory.

Across multiple learning experiences, the CPU was incrementally developed to support a growing instruction set, opcode decoding, datapath control, and branching functionality. Design decisions prioritized correctness, efficient hardware utilization, and compliance with strict structural Verilog constraints.

Key technical aspects of the project include:
- Structural and permitted dataflow SystemVerilog design
- 16-bit arithmetic and logic operations
- Opcode-based instruction decoding
- Datapath and control unit integration
- FPGA simulation and waveform-based verification
- Transistor count and propagation delay analysis

---

## Report 1: Learning Experience C.3 (LEC3)

This report documents the initial development of the 16-bit function unit, including arithmetic, logic, shift operations, and early performance analysis. It establishes the core computational capabilities used throughout the remainder of the CPU design.

<iframe
  src="/files/LEC3Report.pdf"
  width="100%"
  height="900px"
  style="border: none;"
>
</iframe>

<p>
  <a href="/files/LEC3Report.pdf" target="_blank">
    Download LEC3 Report (PDF)
  </a>
</p>

---

## Report 2: Learning Experience F.1 (LEF1)

This report expands the function unit to fully support 16-bit operands, introduces design refinements, and evaluates the implementation in terms of transistor count and propagation delay. The finalized function unit architecture is established here.

<iframe
  src="/files/LEF1Report.pdf"
  width="100%"
  height="900px"
  style="border: none;"
>
</iframe>

<p>
  <a href="/files/LEF1Report.pdf" target="_blank">
    Download LEF1 Report (PDF)
  </a>
</p>

---

## Report 3: Learning Experience F.2 (LEF2)

This report integrates the function unit into a complete CPU datapath. Instruction memory, opcode decoding, and control logic are introduced to enable program execution. Design decisions related to opcode encoding and decoder modification are discussed in detail.

<iframe
  src="/files/LEF2Report.pdf"
  width="100%"
  height="900px"
  style="border: none;"
>
</iframe>

<p>
  <a href="/files/LEF2Report.pdf" target="_blank">
    Download LEF2 Report (PDF)
  </a>
</p>

---

## Report 4: Learning Experience F.3 (LEF3)

This final report adds branching functionality to the CPU, including branch offset computation and program counter control. The completed processor is evaluated through annotated simulations demonstrating correct execution of branch-on-non-negative instructions.

<iframe
  src="/files/LEF3Report.pdf"
  width="100%"
  height="900px"
  style="border: none;"
>
</iframe>

<p>
  <a href="/files/LEF3Report.pdf" target="_blank">
    Download LEF3 Report (PDF)
  </a>
</p>
