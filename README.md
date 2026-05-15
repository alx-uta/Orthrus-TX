# Orthrus-TX

OrthrusTx is a custom high-performance RC transmitter platform built around the STM32H745 microcontroller and designed specifically for modern ExpressLRS-based systems. The project focuses on low-latency control, clean mixed-signal hardware design, modular RF integration, and long-term expandability without unnecessary complexity.

The hardware architecture separates critical analog, digital, and RF sections across an 8-layer PCB stackup to improve signal integrity and reduce noise coupling.

## Features

- STM32H745ZIT6 dual-core MCU
- Dual independent ExpressLRS interfaces
- Modular RF daughterboard design
- Precision filtered analog joystick inputs
- USB connectivity
- SD card support
- Rotary encoders and configurable inputs
- Dedicated analog and digital power domains
- Low-noise mixed-signal PCB layout
- Replaceable battery-oriented design

## Design Goals

OrthrusTx prioritizes:

- Low latency
- High reliability
- Electrical cleanliness
- Modular hardware architecture
- Repairability

## Project Vision

OrthrusTx is being developed both as a functional long-range RC transmitter and as a deep embedded hardware/software engineering project focused on performance, architecture, signal integrity, and system-level design.