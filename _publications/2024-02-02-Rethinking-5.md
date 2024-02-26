---
title: "Rethinking 6-Dof Grasp Detection: A Flexible Framework for High-Quality Grasping"
collection: publications
permalink: /publication/2024-02-02-Rethinking-5
excerpt: 'Robotic grasping is a primitive skill for complex tasks and is fundamental to intelligence. For general 6-Dof grasping, most previous methods directly extract scene-level semantic or geometric information, while few of them consider the suitability for various downstream applications, such as target-oriented grasping.  ...'
date: 2024-02-02
venue: being revised
# paperurl: 
# paperurltext: '[pdf]'
# paperbibtex: 
citation: 'Wei Tang, Siang Chen, Pengwei Xie, Dingchang Hu, Wenming Yang, Guijin Wang'
---
## Abstract

Robotic grasping is a primitive skill for complex tasks and is fundamental to intelligence. For general 6-Dof
grasping, most previous methods directly extract scene-level semantic or geometric information, while few of them consider the suitability for various downstream applications, such as target-oriented grasping. Addressing this issue, we rethink 6-Dof grasp detection from a grasp-centric view and propose a versatile grasp framework capable of handling both scenelevel and target-oriented grasping. Our framework, FlexLoG, is composed of a Flexible Guidance Module and a Local Grasp Model. Specifically, the Flexible Guidance Module is compatible with both global (e.g., grasp heatmap) and local (e.g., visual grounding) guidance, enabling the generation of high-quality grasps across various tasks. The Local Grasp Model focuses on object-agnostic regional points and predicts grasps locally and intently. Experiment results reveal that our framework achieves over 18% and 23% improvement on unseen splits of the GraspNet-1Billion Dataset. Furthermore, real-world robotic tests in three distinct settings yield a 95% success rate.
