---
title: "GAP-RL: Grasps As Points for RL Towards Dynamic Object Grasping"
collection: publications
permalink: /publication/2024-10-04-GraspAsPoints
excerpt: "Dynamic grasping of moving objects in complex, continuous motion scenarios remains challenging. Reinforcement Learning (RL) has been applied in various robotic manipulation tasks, benefiting from its closed-loop property. ..."
date: 2024-10-04
venue: 'IEEE Robotics and Automation Letters'
# paperurl: 
# paperurltext: '[pdf]'
# paperbibtex: 
citation: 'Pengwei Xie, Siang Chen, Qianrun Chen, Wei Tang, Dingchang Hu, Yixiang Dai, Rui Chen, Guijin Wang. (2024). GAP-RL: Grasps As Points for RL Towards Dynamic Object Grasping.'
---
## Abstract

Dynamic grasping of moving objects in complex, continuous motion scenarios remains challenging. Reinforcement Learning (RL) has been applied in various robotic manipulation tasks, benefiting from its closed-loop property. However, existing RL-based methods do not fully explore the potential for enhancing visual representations. In this letter, we propose a novel framework called Grasps As Points for RL (GAP-RL) to effectively and reliably grasp moving objects. By implementing a fast region-based grasp detector, we build a Grasp Encoder by transforming 6D grasp poses into Gaussian points and extracting grasp features as a higher-level abstraction than the original object point features. Additionally, we develop a Graspable Region Explorer for real-world deployment, which searches for consistent graspable regions, enabling smoother grasp generation and stable policy execution. To assess the performance fairly, we construct a simulated dynamic grasping benchmark involving objects with various complex motions. Experiment results demonstrate that our method effectively generalizes to novel objects and unseen dynamic motions compared to other baselines. Real-world experiments further validate the framework's sim-to-real transferability.