---
title: "Region-Centric 6-Dof Grasp Detection: A Data-Efficient Solution for Cluttered Scenes"
collection: publications
permalink: /publication/2024-03-27-Regioncentric-9
excerpt: "Robotic grasping, serving as the cornerstone for complex manipulation tasks, is fundamental for embodied intelligence. For general 6-Dof grasping, most data-driven methods directly extract scene-level information, resorting to fitting with a large amount of data. ..."
date: 2024-03-27
venue: under revision
# paperurl: 
# paperurltext: '[pdf]'
# paperbibtex: 
citation: 'Wei Tang, Siang Chen, Pengwei Xie, Dingchang Hu, Wenming Yang, Guijin Wang. (2024). Region-Centric 6-Dof Grasp Detection: A Data-Efficient Solution for Cluttered Scenes.'
---
## Abstract

Robotic grasping, serving as the cornerstone for complex manipulation tasks, is fundamental for embodied intelligence. For general 6-Dof grasping, most data-driven methods directly extract scene-level information, resorting to fitting with a large amount of data. In this letter, we propose a novel data-efficient 6-Dof grasp detection framework in cluttered scenes, named Region-Centric Grasp Framework (RCGF), consisting of an Iterative Search Module (ISM) and a Region Grasp Model (RGM). Concretely, the ISM aims to retrieve potential region centers and aggregate multiple regions in a coarse-to-fine way. Then, the RGM extracts grasp-related embeddings and predicts grasps within these local regions. Experiments demonstrate that the RCGF significantly outperforms previous arts and can achieve competitive results with only 2% training data, which benefits from the region-centric paradigm and the training-free location strategy. Furthermore, real-world robotic tests in two distinct settings demonstrate the effectiveness of our method with a 95% success rate.