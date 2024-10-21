---
layout: post
title: "Thermal control of an integrated circuit using a Peltier-element"
supervisor: A/Prof Arnfinn A. Eielsen
date: 2024-10-21
---

[comment]: ## Thermal control of an integrated circuit using a Peltier-element

[comment]: *Supervisor: Assoc. prof. Arnfinn A. Eielsen*

This project focusses on managing heat and ensuring constant temperature for an integrated circuit package.

Researchers at the university are making ultra-linear and accurate digital-to-analogue converters (DAC), as an integrated circuit, that can be used for very demanding applications, such as signal generation for nanotechnology applications and measurement of time-varying signals (there is currently no agreed upon standard for measuring time-varying signals!)

Integrated circuits are typically very sensitive to temperature changes, and characteristics will drift. In order to maintain constant characteristics and maintain the validity of calibration data. An integrated circuit is [packaged in a casing](https://en.wikipedia.org/wiki/Integrated_circuit_packaging), and to keep the behaviour as constant as possible, thermal management and control to maintain a constant casing temperature is required.

CERN has recently completed the work on a [analogue-to-digital converter (ADC) based multimeter](https://ohwr.org/project/opt-adc-10k-32b-1cha/-/wikis/home) with similar requirements. In their designs a Peltier-element is used to control the temperature of the ADC package. A [Peltier-element](https://en.wikipedia.org/wiki/Thermoelectric_cooling) is a type of heat-pump that uses the thermoelectric to either heat or cool one of the sides of the element, ideal for small and slow temperature control applications.

![Peltier-element temperature control set-up.](peltier_adc.png "Peltier-element temperature control set-up.")

In this project a complete control system for a Peltier-element will be developed. This includes temperature probes, amplifiers for the Peltier-element, instrumentation for reading temperature and outputting voltage, process modelling, control law design, and real-time implementation on a micro-controller.

**The exact scope, content and outcomes of the project will be agreed upon with the students considering their background and interests.**

### Expected outcomes
- Review of the relevant theory and existing solutions.
- Physical model of the process for simulation and control design.
- System identification of the model parameters.
- Control law design.
- Developing hardware for measuring temperature and amplifier for the element.
- Using a micro-controller with suitable input and output capabilities to interface temperature sensor and amplifier.
- Real-time implementation of control system in C/C++, Rust, or similar.

#### Resources
- Computer with suitable software (e.g. MATLAB/Simulink)
- Lab supplies, e.g. PT-100 element, Peltier-element, heatsink, micro-controller development board, elementary electronic components
