---
decisionKey: "1eee6edb1ae0cbe8b7b784263c4f5e1d0aabff1cd20bd7f26bfc0a9e070fde8b"
language: "zh-CN"
title: "PURe 模块在 ImageNet、CIFAR-10、Galaxy10 与 CT 分割上表现一致提升"
summary: "PURe 是一种基于乘积单元的残差模块，在对数域中以实数形式实现乘法聚合，可改善 Galaxy10 DECaLS、ImageNet、CIFAR-10 与 AMOS CT 分割上的视觉网络精度-参数权衡。该设计使中等深度模型能够以更小的参数预算匹配或超越更深的 ResNet 基线。"
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

这篇 arXiv 预印本提出了 PURe，一个围绕二维乘积单元构建的残差模块。其对数域实数形式使深度残差网络中的乘法局部聚合变得可行，作者将其描述为即插即用的视觉骨干模块。

在 Galaxy10 DECaLS、ImageNet 和 CIFAR-10 上，作者报告 PURe 持续改善残差 CNN，并提供更有利的精度-参数权衡；采用该模块的中等深度模型可以在更小参数预算下匹配或超过明显更深的 ResNet 基线。在 AMOS 基准上，PURe 在 3D 病例级评估下改善了基于切片的 CT 分割。

摘要没有报告改进幅度，也没有与当前最优方法的详细比较，因此难以评估实际影响。该预印本已被 GCPR 2026 接收，但最终同行评审版本和代码尚无法用于独立验证。
