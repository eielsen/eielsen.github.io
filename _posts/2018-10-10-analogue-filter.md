---
layout: post
title: "Arbitrary analogue transfer-function implementation"
supervisor: Assoc. prof. Arnfinn A. Eielsen
date: 2018-10-10
---

[comment]: ## Arbitrary analogue transfer-function implementation

[comment]: *Supervisor: Assoc. prof. Arnfinn A. Eielsen*

This project aims to design and construct a circuit capable of implementing any second-order analogue transfer function (within reasonable limits). The analogue circuit will be configured with digital potentiometers and set by a micro-controller or PC.

In some precision and high bandwidth applications digital signal processing introduces too much distortion and noise, and it may also have insufficient bandwidth. Hence, analogue processing can be a preferable option. One of the main shortcomings with regard to analogue circuitry is the inability to easily change the parameters that determine the response. Many common filter topologies does not allow for easy tuning of transmission zeroes, and it is often cumbersome to tune the poles as well. This makes it difficult (impossible) to implement e.g. model matching control laws, and PID-control is therefore almost always the non-optimal default for analogue control. A programmable analogue filter is desirable as it allows for quick tuning and re-tuning for different processes and applications, without having to make a custom circuit every time.

The arbitrary transfer function will be used for laboratory implementation of low-noise analogue filters and high-speed control systems.

**The exact scope, content and outcomes of the project will be agreed upon with the students considering their background and interests.**

### Expected outcomes
- Reviewing of implementation methods (state-variable filters, gyrators).
- Simulation of possible options (using SPICE or Spectre).
- Designing and building suitable circuits.
- Developing software for control.

#### Resources
- Digital and analog circuit components and ICs.
- Manufacturing of printed circuit boards.
- Micro-controller development kit (with Embedded Coder support).
