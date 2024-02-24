---
title: "Distribution-aware Low-bit Quantization for 3D Point Cloud Networks"
collection: publications
# permalink: /publication/2009-10-01-paper-title-number-1
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-12-13
venue: '2022 IEEE International Conference on Visual Communications and Image Processing (VCIP)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10008887'
citation: 'Dingchang Hu, Siang Chen, Huazhong Yang, Guijin Wang'
---

Various low-bit quantized methods have been widely exploited and shown decent performance on 2D vision tasks in recent years. Complemented with 2D images, 3D point clouds provide an opportunity to understand the surrounding environ-ment better. However, low-bit quantization methods designed for 2D vision tasks are not readily transferable to 3D point clouds due to the higher dimension of 3D data and the increased proportion of activations. In this work, we propose a novel quantization framework, DASCQ, for 3D point cloud processing. First, a new distribution-aware strategy (DA) is presented to decrease the deviation caused by extremely low-bit quantization through activation and weight distribution analysis. Second, a soft constraint manner (SC) is designed to smooth the training of quantized networks which suffer from backward propagation errors. We evaluate our approach on two 3D point cloud datasets, ModelNet40 and S3DIS. Results indicate that the performance of the proposed approach is superior to other state-of-the-art quantization methods on both shape classification and scene semantic segmentation tasks.
