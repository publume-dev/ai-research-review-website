---
decisionKey: "023a98096d79526db38077335ff3b91a40fefef367f6eaae13d83afad7ba21ac"
language: "zh-CN"
title: "新的一阶元学习算法FO-B-MAML具有收敛保证"
summary: "FO-B-MAML是一种新的一阶元学习算法，从双层优化角度推导，收敛到元目标函数的驻点，并引入改进的有限差分梯度估计器，使偏差率提升至O(delta^{2/3})。该算法在保持平坦内存占用的同时，在深度激活密集的CNN和Transformer上接近二阶MAML的性能。"
publishedAt: "2026-08-13T05:50:28.271Z"
score: 0.85
topics:
  - "Meta-Learning"
  - "Optimization"
topicIds:
  - "meta-learning-1l2n8j1"
  - "optimization-wc4i1w"
sourceUrls:
  - "https://arxiv.org/abs/2409.03682"
---

FO-B-MAML是一种基于双层优化视角的一阶MAML变体，引入了将元梯度表达为扰动优化问题解导数的全新形式。传统的一阶方法如FO-MAML和Reptile存在不可约的偏差，而FO-B-MAML旨在克服这一局限性。

FO-B-MAML能收敛到元目标的驻点，这与现有的一阶方法形成对比，后者存在不可约偏差。对称估计器实现的偏差率提升至O(delta^{2/3})，严格优于以往的一阶理论。此外，论文表明MAML目标违反了标准光滑性假设，其光滑常数随元梯度的范数增长，这为使用归一化或裁剪梯度方法（如SNGDM）而非普通梯度下降提供了依据。经验结果显示，FO-B-MAML能达到高精度，紧密跟随二阶MAML的性能，同时绕过“激活瓶颈”，在扩展至深度、激活密集的CNN和Transformer时保持平坦的内存占用。

该研究基于arXiv预印本，尚未经过同行评审。论文未提供所测试的具体数据集或基准，也未提供与现有方法比较的定量性能指标，如精确的准确率数值或内存占用数据。此外，实际收益的泛化性（例如在不同任务族中的表现）仍不明确。
