---
decisionKey: "a9efa6df3ede34d04002dcecb99e48df700c8b1baf7bce2ac1998485c7aa9d98"
language: "zh-CN"
title: "异构迁移学习在高维回归中处理特征不匹配并达到最优误差界"
summary: "新方法通过学习特征映射并填补缺失特征，实现源域与目标域特征集不同的高维回归迁移学习，并提供理论上的最优误差界。"
publishedAt: "2026-08-13T05:50:28.271Z"
score: 0.85
topics:
  - "Transfer Learning"
  - "High-Dimensional Regression"
topicIds:
  - "transfer-learning-lz7sfo"
  - "high-dimensional-regression-1re5qvm"
sourceUrls:
  - "https://arxiv.org/abs/2412.18081"
---

该研究针对高维回归中的迁移学习问题，传统方法通常假设源域和目标域具有相同的特征集。然而现实场景中，源域可能包含目标域没有的特征，导致直接迁移效率低下。作者提出了一种异构迁移学习方法，通过学习特征映射并对目标域缺失的特征进行填补，以利用源域的全部信息。

该方法提供了估计误差和预测误差的上界，并建立了匹配的极小化下界，证明其达到最优收敛速率。理论分析表明，相较于丢弃不可用特征的同构迁移学习，所提出的方法能够实现更低的误差率。

该论文目前为预印本，未经同行评审。摘要仅呈现理论结果，未在真实数据集上进行实验验证，因此实际效果有待进一步检验。
