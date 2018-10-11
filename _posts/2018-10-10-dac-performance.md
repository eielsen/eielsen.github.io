---
layout: post
title: "Universal interfacing and measuring the performance of digital-analog converters"
date: 2018-10-10
---

[comment]: ## Universal interfacing and measuring the performance of digital-analog converters

*Supervisor: Assoc. prof. Arnfinn A. Eielsen*

This project focusses on implementing protocols for various interfaces for data transfer to digital-to-analog converters, and circuits for measuring their performance.

Fair testing and comparison of digital-analog converters is challenging. There are many different interfaces for data transfer to the devices from the control unit. These include parallel buses, serial peripheral interface (SPI), inter-integrated circuit (I²C) bus, inter-IC sound (I²S) bus, and the JESD204 data converter serial interface. The devices also have different voltage output ranges or they have current sourced outputs. This makes is difficult to connect different devices to the same control unit (e.g. micro-controller), and to the same measuring device for signal comparison. In order to simplify testing, an interfacing device that implements the most common data busses (and the deviations from standards that are common among manufacturers) is essential. Furthermore, a low-distortion conditioning amplifier with variable gain is needed to match input and output voltage ranges. A trans-impedance amplifier that converts a current signal to a voltage signal is also necessary in some cases.

**The exact scope, content and outcomes of the project will be agreed upon with the students considering their background and interests.**

### Expected outcomes
- Learning how to use rapid prototyping software to develop protocols for different data transfer interfaces.
- Designing and building interface cards (digital out, analogue in) that can handle several different test devices.
- Learning to select suitable analogue circuit components depending on their dynamic specifications.
- Simulating circuits in SPICE or Spectre.
- Learning how to measure the performance of digital-to-analog converters.

#### Resources
- Digital and analog circuit components and ICs.
- Simulation of possible options (using SPICE or Spectre).
- Manufacturing of printed circuit boards.
- Micro-controller or FPGA development kit (with Embedded or HDL Coder support).
- LabVIEW and/or MATLAB with sufficient licenses for code generation.
