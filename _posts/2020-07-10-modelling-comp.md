---
layout: post
title: "Comparison of thermodynamic modelling and identification approaches for automatic control"
supervisor: A/Prof Arnfinn A. Eielsen, A/Prof Homam Nikpey Somehsaraei, A/Prof Damiano Rotondo
date: 2020-07-10
---

[comment]: ## Comparison of thermodynamic modelling and identification approaches for automatic control

[comment]: *Supervisors: A/Prof Arnfinn A. Eielsen, A/Prof Homam Nikpey Somehsaraei, A/Prof Damiano Rotondo*

Plant modelling in automatic control applications is a primary concern in model-based control approaches due to the potential harmful consequences of erroneous model outputs. For any successful application of model-based control, the models need to accurately predict the response of the system under any number of operating conditions.

Lack of modelling robustness is the main reason machine learning techniques and neural networks (i.e. “artificial intelligence”) have seen very limited uptake in control engineering. Apparently it is difficult to pinpoint the exact cause for the lack of robustness in neural networks due to, among many issues, the combination of a large number of training parameters, non-linearity of the model, non-convexity of the optimisation problem used for training [Nar and Sastry, 2019]. Recently the importance of persistency of excitation of the network weights has been proposed as a method to improve robustness of neural networks.

Traditionally (white-box) physics-based modelling and (grey-/black-box) linear time-invariant (LTI) modelling have been considered best practice for control design and are widely used today. However, these methods also have limitations, as it might be difficult or impossible to determine parameters in some non-linear models, and LTI models may only be suitable for certain system operating points. As a result, such methods may not provide the necessary accuracy and robustness for a given control problem.

Due to the recent advances in analysis of neural networks, it is desirable to evaluate different modelling and identification approaches in order to determine the efficacy of these in a model-based control engineering context.

This project aims to compare
- physics-based modelling and parameter identification, and/or
- linear time-invariant and/or time-varying modelling and identification
- artificial neural networks
as modelling and identification approaches applied to a thermodynamic system.

**The exact scope, content and outcomes of the project will be agreed upon with the students considering their background and interests.**

### Expected outcomes
- learning how to use at least one “traditional” modelling method
- learning how to preform system identification given modelling method
- learning about artificial neural networks and how to train them, applying the method of [Nar and Sastry, 2019]
- learning about persistency of excitation in system identification and neural networks
- learning about experiment design and optimal excitation
- studying methods for model validation, robustness evaluation and comparison of models

### Resources
- computer with suitable software (e.g. MATLAB/Simulink).
- training data from a thermodynamic system

#### References
[Nar and Sastry, 2019] Nar, K & Sastry, S, Persistency of Excitation for Robustness of Neural Networks, 2019 (https://arxiv.org/abs/1911.01043)
