---
title: "Real-time Model Predictive Control and System Identification Using Differentiable Physics Simulation"
collection: publications
permalink: /publication/rtcosi
excerpt: 'Proposing a framework that can planning control steps in real time and adapt to parameter changes under observation and action noise.'
date: 2022-11-03
venue: 'IEEE RA-L'
paperurl: 'https://arxiv.org/abs/2202.09834'
citation: 'S. Chen, K. Werling, C.K Liu. (2022). &quot;Real-time Model Predictive Control and System Identification Using Differentiable Physics Simulation. &quot; <i>IEEE-RAL</i>.'
---
### Abstract
Transferring controller from a simulated environment to physical system is regarded as a challenging problem in robotics. We present a method for continuous improvement of modeling and control after deploying the robot to a dynamically-changing target environment. We develop a differentiable physics simulation framework that performs online system identification and optimal control simultaneously, using the incoming observations from the target environment in real time. To ensure robust system identification against noisy observations, we devise an algorithm to assess the confidence of our estimated parameters, using numerical analysis of the dynamic equations. To ensure real-time optimal control, we adapt the optimization window in the future so that the optimized actions can be replenished faster than consumption, while staying as up-to-date with new information as possible. The constant re-planning based on a constantly improved model allows the robot to swiftly adapt to the changing environment and utilize real-world data in the most sample-efficient way. Thanks to a fast differentiable physics simulator, the optimization for both system identification and control can be solved efficiently for robots operating in real time. We demonstrate our method on a set of examples in simulation and on a real robot and show that our results are favorable compared to baseline methods.

![Hopper can jump on stairs with changing foot damping](/images/rtcosi.gif)
![Damping of foot](/images/hopper.png)

[Download paper here](https://arxiv.org/abs/2202.09834)