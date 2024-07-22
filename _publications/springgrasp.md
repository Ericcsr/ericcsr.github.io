---
title: "SpringGrasp: Synthesizing Compliant, Dexterous Grasps under Shape Uncertainty"
collection: publications
permalink: /publication/springgrasp
excerpt: 'Dexterous precision grasp planning for shape uncertain objects'
date: 2024-07-15
venue: 'Robotics: Science and Systems'
paperurl: 'https://arxiv.org/abs/2404.13532'
citation: 'S. Chen, J. Bohg, C.K Liu. (2024). &quot;SpringGrasp: Synthesizing Compliant, Dexterous Grasps under Shape Uncertainty. &quot; <i>RSS</i>.'
---
### Abstract
Generating stable and robust grasps on arbitrary objects is critical for dexterous robotic hands, marking a significant step towards advanced dexterous manipulation. Previous studies have mostly focused on improving differentiable grasping metrics with the assumption of precisely known object geometry. However, shape uncertainty is ubiquitous due to noisy and partial shape observations, which introduce challenges in grasp planning. We propose, SpringGrasp planner, a planner that considers uncertain observations of the object surface for synthesizing compliant dexterous grasps. A compliant dexterous grasp could minimize the effect of unexpected contact with the object, leading to more stable grasp with shape-uncertain objects. We introduce an analytical and differentiable metric, SpringGrasp metric, that evaluates the dynamic behavior of the entire compliant grasping process. Planning with SpringGrasp planner, our method achieves a grasp success rate of 89% from two viewpoints and 84% from a single viewpoints in experiment with a real robot on 14 common objects. Compared with a force-closure based planner, our method achieves at least 18% higher grasp success rate.

![Fast forward video](/images/springgrasp_teaser.jpg)

[Paper](https://arxiv.org/abs/2404.13532)
[Website](https://stanford-tml.github.io/SpringGrasp/)
[Code](https://github.com/Stanford-TML/SpringGrasp_release)