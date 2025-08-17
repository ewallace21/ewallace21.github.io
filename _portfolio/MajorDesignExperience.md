---
title: "Senior Major Design Experience"
excerpt: "Open-source hardware Trusted Platform Module, sponsored by Lenovo.<br/><img src='/images/jiv.jpg'>"
collection: portfolio
---
## Overview

This project is an open-source hardware implementation of a **Trusted Platform Module (TPM)** built on an FPGA, following the **TPM 2.0 specification** from the Trusted Computing Group (TCG). Designed for integration within a **Datacenter Secure Control Module (DC-SCM)** architecture, this work aims to provide a verifiable and modifiable platform security solution for modern data center environments.

The project includes a complete system design covering:
- An **I/O interface module** for SPI communication with the host system
- A **management controller** for operational state transitions
- An **execution engine** to handle TPM command processing

The current implementation focuses on architectural framework and module-level communication in preparation for full TPM 2.0 functionality to be completed by future development teams.

## Goals

- Develop an open-source, hardware-based TPM accessible for FPGA users  
- Avoid reliance on proprietary or platform-specific IP cores  
- Establish a verified design foundation for future standards-compliant TPM implementations

## Technical Highlights

- Compliant with **SPI Mode 0 (3.3V, 24 MHz)** per TCG PC Client Profile  
- Designed using **Verilog HDL** for FPGA deployment  
- Structured for portability across general-purpose FPGAs  
- All work licensed under an **open-source license** to promote transparency and security research

## Motivation

While software-based TPMs exist, they lack the physical trust assurances needed in secure hardware environments. A hardware-based, open-source TPM provides greater transparency, facilitates independent verification, and helps mitigate firmware-level attacks—an increasingly important consideration in high-assurance systems.
