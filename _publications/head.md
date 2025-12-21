---
title: "Hand-Eye Autonomous Delivery: Learning Humanoid Navigation, Locomotion and Reaching"
collection: publications
permalink: /publication/head
excerpt: 'Scaling up robot datat collection with high quality human data'
date: 2025-09-20
venue: 'Conference on Robot Learning'
paperurl: 'https://arxiv.org/abs/2508.03068'
citation: 'S. Chen, Y. Ye, Z. Cao, J. Lew, P. Xu, C.K. Liu. (2025). &quotHand-Eye Autonomous Delivery: Learning Humanoid Navigation, Locomotion and Reaching. &quot; <i>CoRL</i>.'
---
### Abstract
We propose Hand-Eye Autonomous Delivery, a framework that learns navigation, locomotion, and reaching skills for humanoids, directly from human motion and vision perception data. We take a modular approach where the high-level planner commands the target position and orientation of the hands and eyes of the humanoid, delivered by the low-level policy that controls the whole-body movements. Specifically, the low-level whole-body controller learns to track the three points (eyes, left hand, and right hand) from existing large-scale human motion capture data while high-level policy learns from human data collected by Aria glasses. Our modular approach decouples the ego-centric vision perception from physical actions, promoting efficient learning and scalability to novel scenes. We evaluate our method both in simulation and in the real-world, demonstrating humanoid's capabilities to navigate and reach in complex environments designed for humans.

![Fast forward video](/images/head.gif)

[Paper](https://arxiv.org/abs/2508.03068)
[Website](https://stanford-tml.github.io/HEAD/)
[Code](https://github.com/Stanford-TML/HEAD_release)