---
title: "Grasp as Points: A Novel Grasp Representation Guided RL Policy for Dynamic Object Grasping"
collection: publications
permalink: /publication/2024-06-07-GraspAsPoints
excerpt: "Dynamic grasping of moving objects in complex, continuous motion scenarios with limited observation remains a challenging task. In this letter, we propose a reinforcement learning framework for effective and robust dynamic object grasping. ..."
date: 2024-03-27
venue: under review
# paperurl: 
# paperurltext: '[pdf]'
# paperbibtex: 
citation: 'Pengwei Xie, Siang Chen, Wei Tang, Dingchang Hu, Guijin Wang. (2024). Grasp as Points: A Novel Grasp Representation Guided RL Policy for Dynamic Object Grasping.'
---
## Abstract

Dynamic grasping of moving objects in complex, continuous motion scenarios with limited observation remains a challenging task. In this letter, we propose a reinforcement learning framework for effective and robust dynamic object grasping. Our approach leverages recent work to obtain real-time, high-quality grasp candidates as observations. To fully exploit grasp features, we transform the grasp candidates into a set of Gaussian points representing 6D poses and design a hierarchical GraspPointsGroupNet to extract geometric features. We construct a simulated dynamic grasping benchmark tasked with grasping objects undergoing various complex motions. Evaluations on this benchmark demonstrate our method's ability to generalize to novel objects and unseen dynamic motions. Furthermore, real-world experiments validate the framework's sim-to-real transferability, showcasing promising results in dynamic grasping. Our framework paves the way for robust robotic grasping of dynamically moving objects in unstructured environments.