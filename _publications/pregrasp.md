---
title: "Synthesize Dexterous Nonprehensile Pregrasp for Ungraspable Objects"
collection: publications
permalink: /publication/pregrasp
excerpt: 'A framework for dexterous nonprehensile pregrasp manipulation for initially occluded ungraspable objects'
date: 2023-07-15
venue: 'SIGGRAPH Conference proceedings 2023'
paperurl: 'https://arxiv.org/abs/2305.04654'
citation: 'S. Chen, A. Wu, C.K Liu. (2023). &quot;Synthesize Dexterous Nonprehensile Pregrasp for Ungraspable Objects. &quot; <i>SIGGRAPH</i>.'
---
### Abstract
Daily objects embedded in a contextual environment are often ungraspable initially. Whether it is a book sandwiched by other books on a fully packed bookshelf or a piece of paper lying flat on the desk, a series of nonprehensile pregrasp maneuvers is required to manipulate the object into a graspable state. Humans are proficient at utilizing environmental contacts to achieve manipulation tasks that are otherwise impossible, but synthesizing such nonprehensile pregrasp behaviors is challenging to existing methods. We present a novel method that combines graph search, optimal control, and a learning-based objective function to synthesize physically realistic and diverse nonprehensile pre-grasp motions that leverage the external contacts. Since the ``graspability'' of an object in context with its surrounding is difficult to define, we utilize a dataset of dexterous grasps to learn a metric which implicitly takes into account the exposed surface of the object and the finger tip locations. Our method can efficiently discover hand and object trajectories that are certified to be physically feasible by the simulation and kinematically achievable by the dexterous hand. We evaluate our method on eight challenging scenarios where nonprehensile pre-grasps are required to succeed. We also show that our method can be applied to unseen objects different from those in the training dataset. Finally, we report quantitative analyses on generalization and robustness of our method, as well as an ablation study.

![Fast forward video](/images/pregrasp.gif)

[Download paper here](https://arxiv.org/abs/2305.04654)
[Code here](https://github.com/Ericcsr/synthesize_pregrasp)