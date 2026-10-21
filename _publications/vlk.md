---
title: "VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes"
collection: publications
permalink: /publication/vlk
excerpt: 'Learning perception-based humanoid loco-manipulation from synthetic vision-language-kinematics data'
date: 2026-10-02
venue: 'Conference on Robot Learning'
paperurl: 'https://arxiv.org/abs/2606.30645'
citation: 'Y. Wang, J. Li, S. Chen, T. Truong, P. Xu, P. Abbeel, R. Duan, K. Sreenath, A. Kanazawa, C. Sferrazza, G. Shi, C.K. Liu. (2026). &quot;VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes.&quot; <i>CoRL</i>.'
header:
  teaser: "vlk_teaser.jpg"
redirect_from:
  - /publications/vlk
  - /publications/vlk/
---
### Abstract
Perception-based humanoid loco-manipulation requires connecting egocentric observations and task instructions to whole-body motion. Learning this mapping requires synchronized egocentric images, language commands, and robot-compatible kinematic trajectories, yet no existing data source provides this complete tuple at scale. We address this bottleneck by generating vision-language-kinematics (VLK) supervision synthetically in reconstructed scenes. Our pipeline leverages 3D Gaussian Splatting to reconstruct metric-scale indoor environments, synthesizes navigation and object-interaction trajectories using privileged scene information, and renders paired egocentric observations after the fact. We produce 48,000 paired trajectories with no human intervention and train a VLK policy that predicts short-horizon whole-body kinematic trajectories. A whole-body tracker converts these predictions into actions on the physical humanoid. We evaluate on the physical Unitree G1 performing navigation and single-object transport, demonstrating that synthesized interactions in reconstructed scenes provide effective supervision for sim-to-real perception-based humanoid loco-manipulation.

![Teaser](/images/vlk_teaser.jpg)

[Paper](https://arxiv.org/abs/2606.30645)
[Website](https://vision-language-kinematics.github.io/)
