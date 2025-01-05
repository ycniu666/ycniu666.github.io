---
title: "PerfTop: Towards performance prediction of distributed learning over general topology"
collection: publications
permalink: /publications/2024_JPDC_Changzhi
label: 2024_JPDC_Changzhi
excerpt: 'Changzhi Yan, Zehan Zhu, Youcheng Niu, Cong Wang, Cheng Zhuo, and Jinming Xu'
date: 2025-5-28
venue: 'Journal of Parallel and Distributed Computing'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0743731524000868'
authors: 'Changzhi Yan, Zehan Zhu, Youcheng Niu, Cong Wang, Cheng Zhuo, and Jinming Xu'
---

Abstract: Distributed learning with multiple GPUs has been widely adopted to accelerate the training process of large-scale deep neural networks. However, misconfiguration of the GPU clusters with various communication primitives and topologies could potentially diminish the gains in parallel computation and lead to significant degradation in training efficiency. Predicting the performance of distributed learning enables service providers to identify potential bottlenecks beforehand. In this work, we propose a Performance prediction framework over General Topologies, called PerfTop, for accurate estimation of per-iteration execution time. The main strategy is to integrate computation time prediction with an analytical model to map the nonlinearity in communication and fine-grained computation-communication patterns. This enables accurate prediction of a variety of neural network models over general topologies, such as tree, hierarchical, and exponential. Our extensive experiments show that PerfTop outperforms existing methods in estimating both computation and communication time, particularly for communication, surpassing the existing methods by over 45%. Meanwhile, it achieves an accuracy of above 85% in predicting the execution time over general topologies compared to simple topologies such as star and ring from the previous works.
