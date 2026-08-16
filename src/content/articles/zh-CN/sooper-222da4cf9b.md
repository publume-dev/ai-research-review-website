---
decisionKey: "222da4cf9b6e46187123ad213542d26bdd1cc733b01d2d85742174245f0ceba0"
language: "zh-CN"
title: "SOOPER：以保守策略为先验的安全探索强化学习方法"
summary: "SOOPER 利用概率动力学模型，在乐观探索与悲观回退之间平衡，以实现安全强化学习，并在理论保证和实验中表现优于现有方法。"
publishedAt: "2026-08-16T03:16:05.622Z"
score: 0.85
topics:
  - "Reinforcement Learning"
  - "Safe Exploration"
topicIds:
  - "reinforcement-learning-pvp23c"
  - "safe-exploration-13y8hf9"
sourceUrls:
  - "https://arxiv.org/abs/2601.19612"
---

安全强化学习旨在训练智能体在探索环境时避免危险行为。SOOPER 方法提出使用概率动力学模型来建模环境不确定性，并利用一个保守的策略先验作为安全回退。该研究在多个安全强化学习基准和真实硬件上进行了实验。

SOOPER 的核心机制是在乐观探索与悲观回退之间切换：当模型不确定性低时采取乐观探索，否则回退到保守策略。该方法提供了理论保证，包括学习过程中的安全性保证以及通过界定累积遗憾来保证收敛到最优策略。实验表明，SOOPER 在关键安全强化学习基准和真实硬件上可扩展，并优于最先进的方法。

论文摘要中提到了理论保证，但具体条件和假设未详细说明。此外，该论文为预印本，未经同行评审。
