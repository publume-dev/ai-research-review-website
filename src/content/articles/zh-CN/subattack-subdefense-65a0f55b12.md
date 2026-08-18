---
decisionKey: "65a0f55b12c9cf7fc83a85e92ba99ab6f33f3ba6d11e5e7b35dabca3010be0a9"
language: "zh-CN"
title: "揭示未学习扩散模型中的线性子空间：SubAttack 与 SubDefense"
summary: "一项新研究揭示了未学习扩散模型中被擦除的概念以线性子空间形式保留，并提出了更强大的攻击和防御方法。"
publishedAt: "2026-08-18T03:10:36.725Z"
score: 0.82
topics:
  - "Diffusion Models"
  - "Machine Learning Security"
topicIds:
  - "diffusion-models-1torb32"
  - "machine-learning-security-12tncy"
sourceUrls:
  - "https://arxiv.org/abs/2504.21307"
---

扩散模型常常通过‘未学习’（unlearning）来移除不安全或受版权保护的概念。然而，该研究发现，即使模型已被训练以生成特定概念，该概念仍然以连贯的、可解释的线性子空间形式存在于词嵌入空间中。

论文提出了一种名为 SubAttack 的攻击方法，它学习一组正交的攻击令牌嵌入，这些嵌入是文本元素的线性组合。这些组合揭示了未学习模型通过相关的文本组件保留了目标概念。SubAttack 在跨文本提示、初始噪声和未学习模型方面比之前的攻击更强大且更具迁移性。相应地，他们提出的防御方法 SubDefense 通过投影出发现的子空间，提供了比现有防御更强的鲁棒性，同时更好地保持了安全生成的质量。

该论文目前是预印本，未经同行评审。因此，实验结果的稳健性和发现的可推广性尚未得到独立验证。
