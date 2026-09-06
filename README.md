# Lab 09 – Pipeline Hazards, Stalls & Advanced Reasoning

CS2053 – Computer Architecture  
Department of Computer Science and Engineering, University of Moratuwa

## Overview

- Load-use data hazards requiring mandatory pipeline stalls (bubbles)
- Hazard detection unit control logic and pipeline register interlocks
- Software-based hazard avoidance: instruction scheduling and NOP insertion
- CPI (Cycles Per Instruction) degradation analysis under pipeline stalls and flushes

## Theory Alignment

- Canonical lecture concepts, ISA specifications, and architecture theory are documented in the [CS2053-Weekly-Notes](https://github.com/CS2053-Computer-Architecture/CS2053-Weekly-Notes) repository.

## Repository Structure

```text
.
├── src/
├── traces/
├── analysis/
├── evidence/
└── README.md
```

## Engineering & Git Standards

- **Commit Conventions**: All commits follow the Conventional Commits format (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`).
- **Branching Workflow**: Assembly programs, processor simulations, and analysis tasks utilize feature branches prior to merging into `main`.
- **Reproducibility**: Register trace tables, Ripes simulation screenshots, and benchmark logs are preserved in `evidence/`.

## Academic Context

Department of Computer Science and Engineering, University of Moratuwa.
