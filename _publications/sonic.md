---
title: "SONIC: Supersizing Motion Tracking for Natural Humanoid Whole-Body Control"
collection: publications
permalink: /publication/sonic
excerpt: 'Scaling up humanoid robot control via motion tracking'
date: 2026-07-01
venue: 'Science Robotics'
paperurl: 'https://arxiv.org/abs/2511.07820'
citation: 'Z. Luo, Y. Yuan, T. Wang, C. Li, S. Chen, F. Castaneda, Z. Cao, X. Da, etc. (2026). &quot;SONIC: Supersizing Motion Tracking for Natural Humanoid Whole-Body Control.&quot; <i>Science Robotics</i>.'
header:
  teaser: "sonic.gif"
---
### Abstract
Despite the rise of billion-parameter foundation models trained across thousands of GPUs, similar scaling gains have not been shown for humanoid control. Current neural controllers for humanoids remain modest in size, target a limited set of behaviors, and are trained on a handful of GPUs over several days. We show that scaling up model capacity, data, and compute yields a generalist humanoid controller capable of creating natural and robust whole-body movements. Specifically, we posit motion tracking as a natural and scalable task for humanoid control, leveraging dense supervision from diverse motion-capture data to acquire human motion priors without manual reward engineering. We build a foundation model for motion tracking by scaling along three axes: network size (from 1.2M to 42M parameters), dataset volume (over 100M frames, 700 hours of high-quality motion data), and compute (9k GPU hours). Beyond demonstrating the benefits of scale, we show the practical utility of our model through two mechanisms: (1) a real-time universal kinematic planner that bridges motion tracking to downstream task execution, enabling natural and interactive control, and (2) a unified token space that supports various motion input interfaces, such as VR teleoperation devices, human videos, and vision-language-action (VLA) models, all using the same policy. Scaling motion tracking exhibits favorable properties: performance improves steadily with increased compute and data diversity, and learned representations generalize to unseen motions, establishing motion tracking at scale as a practical foundation for humanoid control.

![Fast forward video](/images/sonic.gif)

[Paper](https://arxiv.org/abs/2511.07820)
[Website](https://nvlabs.github.io/SONIC/)