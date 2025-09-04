---
title: "Region-Centric 6-Dof Grasp Detection: A Data-Efficient Solution for Cluttered Scenes"
collection: publications
permalink: /publication/2025-06-23-Regioncentric-9
excerpt: "Robotic grasping, serving as the cornerstone of robot manipulation, is fundamental for embodied intelligence. Manipulation in challenging scenarios demands grasp detection algorithms with higher efficiency and generalizability. ..."
date: 2025-06-23
venue: IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2025
# paperurl: 
# paperurltext: '[pdf]'
# paperbibtex: 
citation: 'Siang Chen, Wei Tang, Pengwei Xie, Dingchang Hu, Wenming Yang, Guijin Wang. (2025). Region-Centric 6-Dof Grasp Detection: A Data-Efficient Solution for Cluttered Scenes.'
---
## Abstract

Robotic grasping, serving as the cornerstone of robot manipulation, is fundamental for embodied intelligence. Manipulation in challenging scenarios demands grasp detection algorithms with higher efficiency and generalizability. However, for general 6-Dof grasp detection, most data-driven methods directly extract scene-level features to generate grasp prediction, relying on a relatively heavy scene-level feature encoder and a significant amount of data with dense grasp labels for model training. In this letter, we propose a novel data-efficient 6-Dof grasp detection framework in cluttered scenes, named Region-Centric Grasp Detection (RCGD), consisting of an Iterative Search Module (ISM) and a Region Grasp Model (RGM). Concretely, ISM aims to retrieve potential region centers and aggregate multiple regions in a coarse-to-fine way. Then, RGM extracts aligned grasp-related embeddings and predicts grasps within these local regions. Benefiting from the region-centric paradigm and the training-free location strategy, RCGD significantly outperforms previous methods and shows minimal performance loss with even a very small portion of training data or labels. Furthermore, real-world robotic experiments in two distinct settings highlight the effectiveness of our method with a 95 % success rate.