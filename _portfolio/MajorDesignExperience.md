---
title: "Senior Major Design Experience"
excerpt: "Open-source hardware Trusted Platform Module, sponsored by Lenovo.<br/><img src='/images/tpm.png'>"
collection: portfolio
---
## Overview

As **Team Lead**, I am currently guiding the development of the foundational framework for a fully open-source FPGA implementation of a **Trusted Platform Module (TPM 2.0)**. This system is being designed in alignment with the **Trusted Computing Group (TCG) specification** and is intended for integration into **Datacenter Secure Control Module (DC-SCM)** architectures.

This is a **multi-phase, ongoing initiative** launched by our senior design team as part of our capstone engineering experience, and is sponsored and guided by Lenovo. Our focus is on architecting and implementing the core framework, establishing a strong technical and documentation foundation for future teams to expand upon. The first phase of the project is scheduled for completion by **October 31, 2025**.

Our work aims to deliver a transparent, extensible, and secure hardware security solution capable of being independently verified and freely adapted for research, commercial, or educational use.

### Current Focus:
- Implementation of a modular control and execution framework in Verilog
- Designing communication interfaces between the TPM logic and host via SPI
- Building and testing internal state machines and data buffers for command processing

## My Role

As the project’s **Team Lead**, I am responsible for:
- Defining system-level architecture and module responsibilities
- Coordinating cross-functional collaboration within the team
- Ensuring adherence to open-source licensing and TPM 2.0 protocol specifications
- Overseeing verification, documentation, and milestone tracking

## Goals

- Deliver a hardware-based TPM compliant with TPM 2.0 over SPI  
- Maintain portability across general-purpose FPGAs (no vendor lock-in)  
- Establish a foundation for future teams to implement cryptographic modules  
- Contribute to the transparency and auditability of hardware security

## Technical Highlights

- Interface: **3.3V SPI (Mode 0), 24 MHz**, per TCG Client TPM Profile  
- Language: **Verilog HDL**, designed for portability across FPGA platforms  
- Modular design for separation of I/O, control, execution, and buffering  
- Fully open-source under a permissive license, hosted on GitHub

## Motivation

Existing TPM implementations are predominantly software-based or proprietary, limiting both trust and transparency in secure hardware systems. This project provides an alternative: a **hardware-based, open-source TPM** designed for open verification and extensibility—key principles in modern cybersecurity and trusted computing.
