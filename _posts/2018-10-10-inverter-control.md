---
layout: post
title: "Designing and controlling a power inverter (DC to AC)"
supervisor: A/Prof Arnfinn A. Eielsen
date: 2018-10-10
---

[comment]: ## Designing and controlling a power inverter (DC to AC)

[comment]: *Supervisor: Assoc. prof. Arnfinn A. Eielsen*

This project focusses on modelling inverters for simulation and controlling the quality of the inverter output.

The last few years have seen rapid developments in the area of power electronics, including new switching devices, new topologies and new control algorithms. With new renewable energy generation targets being set as well as emerging capabilities due to improved battery technology, inverters are key to transparent conversion between power distribution domains. Reducing energy loss due to the non-ideal switching action (causing distortion) in these devices is therefore a primary concern.

Controlling a switching signal converters is typically done in a feed-forward fashion using pulse width modulation (PWM) strategies, such as carrier-based PWM and space vector modulation. Both are well understood and their theoretical distortion spectra can be calculated, hence neither method can sufficiently suppress distortion. Noise-shaping (NS) and model predictive control (MPC) are known to improve inverter modulation. MPC can also incorporate additional constraints in order to minimise losses.

Students attempting the project will do a review of available literature on suitable circuit topologies, transistors, PWM, NS and MPC. An algorithm minimising a cost function (e.g. the tracking error) will be developed. Additional considerations (e.g. switching losses) will be considered. Then, for given parameters of the system, the algorithm should be implemented in a simulation environment (e.g. Simulink) and demonstrated.

A complementary project has been created to design and build an inverter prototype that the control algorithm potentially can be tested on.

**The exact scope, content and outcomes of the project will be agreed upon with the students considering their background and interests.**

### Expected outcomes
- Reviewing of the relevant theory from power electronics and control engineering.
- Developing physical models for simulation of inverter circuits.
- Determining criteria for evaluating inverter performance (distortion, power losses).
- Developing a control method for improved switching, using e.g. noise-shaping or model predictive control.
- Simulating control methods using physical models.
- Evaluating control methods with respect to previously found criteria.
- Potentially trying out the control method on an inverter prototype (see complementary project).

#### Resources
- Computer with suitable software (e.g. MATLAB/Simulink).
