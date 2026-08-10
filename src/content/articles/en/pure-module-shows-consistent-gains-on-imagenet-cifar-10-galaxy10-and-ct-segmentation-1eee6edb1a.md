---
decisionKey: "1eee6edb1ae0cbe8b7b784263c4f5e1d0aabff1cd20bd7f26bfc0a9e070fde8b"
language: "en"
title: "PURe Module Shows Consistent Gains on ImageNet, CIFAR-10, Galaxy10, and CT Segmentation"
summary: "PURe, a product-unit residual module that performs multiplicative aggregation through a real-valued log-domain formulation, improves the accuracy-to-parameter trade-off for vision networks on Galaxy10 DECaLS, ImageNet, CIFAR-10, and AMOS CT segmentation. The design lets moderately deep models match or surpass much deeper ResNet baselines with smaller parameter budgets."
publishedAt: "2026-08-10T15:13:40.453Z"
score: 0.85
topics:
  - "Computer Vision"
  - "Neural Network Architecture"
  - "Multiplicative Interactions"
topicIds:
  - "computer-vision-ykrxu8"
  - "neural-network-architecture-59qnkb"
  - "multiplicative-interactions-1t4n8zw"
sourceUrls:
  - "https://arxiv.org/abs/2505.04397"
---

The arXiv preprint introduces PURe, a residual module built around a 2D product unit. Its real-valued log-domain formulation is presented as making multiplicative local aggregation practical inside deep residual networks, and the module is described as plug-and-play for vision backbones.

On Galaxy10 DECaLS, ImageNet, and CIFAR-10, the authors report that PURe consistently improves residual CNNs and yields a more favorable accuracy-parameter trade-off. Moderately deep models using the module can match or surpass substantially deeper ResNet baselines with smaller parameter budgets. On AMOS, PURe also improves slice-based CT segmentation under 3D case-level evaluation.

The abstract does not report the magnitude of the improvements or detailed comparisons with current state-of-the-art methods, so the practical impact is hard to gauge. The preprint is accepted to GCPR 2026, but the final peer-reviewed version and code are not yet available for independent verification.
