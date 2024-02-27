---
title: "Uncertainty-Aware Laser Stripe Segmentation with Non-Local Mechanisms for Welding Robots"
collection: publications
permalink: /publication/2024-02-27-Uncertainty-7
excerpt: 'The line-structured-light system has been widely applied in intelligent welding robots for weld seam reconstruction and tracking. However, it's challenging to extract the projected laser stripes from captured images due to the strong noise and high dynamic range in welding environments. ...'
date: 2024-02-27
venue: under review
# paperurl: 
# paperurltext: '[pdf]'
# paperbibtex: 
citation: 'Yixiang Dai, Siang Chen, Tianyu Sun, Zimo Fan, Chun Zhang, Xiaobing Feng, Guijin Wang'
---
## Abstract

The line-structured-light system has been widely applied in intelligent welding robots for weld seam reconstruction and tracking. However, it's challenging to extract the projected laser stripes from captured images due to the strong noise and high dynamic range in welding environments. In this work, we propose an uncertainty-aware non-local laser stripe segmentation network(UNLS-Net) to accurately extract laser stripes under real-world challenging welding scenes. The uncertainty-aware policy is designed to refine the coarse results based on epistemic-aleatoric combined uncertainty maps. Further a non-local module is presented to increase spatial correlation, thus maintaining the laser continuity. Experiments are conducted on our large-scale and shape-various laser stripe dataset captured from real-world welding scenarios, which containing 3,136 welding images. Compared with previous segmentation networks applied in this task, our method achieves significantly better performance and can make a trade-off between effectiveness and efficiency by changing the uncertainty iterations during inference.