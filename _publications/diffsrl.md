---
title: "DiffSRL: Learning Dynamic-aware State Representation for Deformable Object Control with Differentiable Simulator"
collection: publications
permalink: /publication/diffsrl
excerpt: 'Using differentiable physics engine to learn low dimension state representation of deformable object.'
date: 2021-10-22
venue: 'IEEE RA-L'
paperurl: 'https://arxiv.org/abs/2110.12352'
citation: 'S. Chen,Y. Liu, S. Yao, J. Li, T. Fan, J. Pan. (2022). &quot;DiffSRL: Learning Dynamical State Representation for Deformable Object Manipulation with Differentiable Simulator. &quot; <i>IEEE-RAL</i>.'
---

### Abstract
Dynamic state representation learning is essential for robot learning. Good latent space that can accurately describe dynamic transition and constraints can significantly accelerate reinforcement learning training as well as reduce motion planning complexity. However, deformable object have very complicated dynamics and is hard to be represented directly by a neural network without any prior physics information. We propose DiffSRL, an end-to-end dynamic state representation learning pipeline that uses differentiable physics engine to teach neural network how to represent high dimensional pointcloud data collected from deformable objects. Our specially designed loss function can guide neural network aware physics constraints and feasibility. We benchmark the performance of our methods as well as other state representation algorithms with multiple downstream tasks on PlasticineLab. Our model demonstrates superior performance most of the time on all tasks. We also demonstrate our model's performance in real hardware setting with two manipulation tasks on a UR-5 robot arm.

[Download paper here](https://ieeexplore.ieee.org/document/9833281)
[More Experiment Result & Code](https://ericcsr.github.io/DiffSRL)