---
decisionKey: "4e36fb6267dd1840be260fb8a7a44c25f750bb98ed326b61667d071f6f8aa3cd"
language: "zh-CN"
title: "高维高斯混合模型下迭代伪标签自训练的精确渐近理论"
summary: "一篇被 JMLR 接收的理论论文刻画了在岭正则线性分类器上使用伪标签进行迭代自训练的性能边界，并针对标签不平衡提出了修正策略。该结果让这一常用启发式方法获得了严谨的渐近理论基础。"
publishedAt: "2026-08-11T18:46:48.986Z"
score: 0.82
topics:
  - "Self-training Theory"
  - "Semi-supervised Learning"
  - "High-dimensional Statistics"
topicIds:
  - "self-training-theory-1xblht9"
  - "semi-supervised-learning-1miumji"
  - "high-dimensional-statistics-18910x4"
sourceUrls:
  - "https://arxiv.org/abs/2205.07739"
---

自训练是半监督学习中一种常见技术，但其行为尚未被完全理解。这篇论文在输入维度和数据规模成比例增长的高维框架下，分析作用于二元高斯混合数据上的岭正则凸损失线性分类器的迭代自训练过程，并给出了精确的渐近刻画。作者还指出，根据 arXiv 上的 camera-ready 版本，该论文已被《Journal of Machine Learning Research》（JMLR）接收。

论文的结论区分了两种不同的迭代机制。在迭代次数较少时，自训练通过拟合相对可靠的伪标签并进行大幅参数更新来提升泛化性能；而在迭代次数较多时，它通过小幅的软标签更新和较小的正则化逐步改进分类平面的方向。面对标签不平衡时，自训练在真实标签监督学习下表现不佳；论文提出了两种启发式方法，即使标签不平衡显著，也能使自训练性能接近监督学习。

该结论是渐近性的，并且局限于二元高斯混合模型。论文摘要未提供真实数据集上的实验证据，因此在该设定之外的实际影响仍有待验证。
