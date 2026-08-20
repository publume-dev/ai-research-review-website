---
decisionKey: "9aea5ab13391e7d1e494025127c9b7213d4b7d1d1c76f8e17543580b9507c42d"
language: "zh-CN"
title: "弱到强泛化的布雷格曼偏差-方差分解理论"
summary: "新理论通过布雷格曼散度分解弱到强泛化中的风险差距，无需学生假设类的凸性，并为平方损失和交叉熵损失提供了改进策略。"
publishedAt: "2026-08-20T14:09:19.508Z"
score: 0.82
topics:
  - "Weak-to-Strong Generalization"
  - "Bias-Variance Decomposition"
  - "Bregman Divergence"
  - "Machine Learning Theory"
topicIds:
  - "weak-to-strong-generalization-1muolft"
  - "bias-variance-decomposition-llek5b"
  - "bregman-divergence-16qw15r"
  - "machine-learning-theory-r9f4fp"
sourceUrls:
  - "https://arxiv.org/abs/2505.24313"
---

弱到强泛化研究的是如何利用弱模型的监督来训练更强的模型。该论文提出一种基于布雷格曼散度的广义偏差-方差分解，用于刻画学生模型与教师模型之间的总体风险差距。

对于平方损失，论文给出了学生模型收敛到后验均值教师模型的充分条件，并表明增大模型规模可确保收敛。对于交叉熵损失，分析指出降低学生预测分布的熵可促进弱到强泛化，且反向交叉熵对教师预测不确定性不如前向交叉熵敏感。实验表明，纳入反向交叉熵能一致地提升弱到强设置下的学生表现。

摘要描述了理论和实证验证，但未提供具体的定量结果或数据集细节，这些通常是全面评估实际意义所必需的。
