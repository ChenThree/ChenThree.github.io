---
title: "Distribution-aware Low-bit Quantization for 3D Point Cloud Networks"
collection: publications
permalink: /publication/2022-12-13-Distribution-1
excerpt: 'Various low-bit quantized methods have been widely exploited and shown decent performance on 2D vision tasks in recent years. Complemented with 2D images, 3D point clouds provide an opportunity to understand the surrounding environ-ment better. However, low-bit quantization methods designed for 2D vision tasks are not readily transferable to 3D point clouds due to the higher dimension of 3D data and the increased proportion of activations. ...'
date: 2022-12-13
venue: '2022 IEEE International Conference on Visual Communications and Image Processing (VCIP)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10008887'
paperurltext: '[pdf]'
paperbibtex: 'https://scholar.googleusercontent.com/scholar.bib?q=info:D5RjuybFJy4J:scholar.google.com/&output=citation&scisdr=ClEU8UAgELqZw3Kk6bQ:AFWwaeYAAAAAZdmi8bTxWEfpsuHgRAtFWb6HayQ&scisig=AFWwaeYAAAAAZdmi8V8FUQS7CJWMiSEmzSToumE&scisf=4&ct=citation&cd=-1&hl=en'
citation: 'Hu, D., Chen, S., Yang, H., & Wang, G. (2022, December). Distribution-aware Low-bit Quantization for 3D Point Cloud Networks. In 2022 IEEE International Conference on Visual Communications and Image Processing (VCIP) (pp. 1-5). IEEE.'
---
## Abstract

Various low-bit quantized methods have been widely exploited and shown decent performance on 2D vision tasks in recent years. Complemented with 2D images, 3D point clouds provide an opportunity to understand the surrounding environ-ment better. However, low-bit quantization methods designed for 2D vision tasks are not readily transferable to 3D point clouds due to the higher dimension of 3D data and the increased proportion of activations. In this work, we propose a novel quantization framework, DASCQ, for 3D point cloud processing. First, a new distribution-aware strategy (DA) is presented to decrease the deviation caused by extremely low-bit quantization through activation and weight distribution analysis. Second, a soft constraint manner (SC) is designed to smooth the training of quantized networks which suffer from backward propagation errors. We evaluate our approach on two 3D point cloud datasets, ModelNet40 and S3DIS. Results indicate that the performance of the proposed approach is superior to other state-of-the-art quantization methods on both shape classification and scene semantic segmentation tasks.
