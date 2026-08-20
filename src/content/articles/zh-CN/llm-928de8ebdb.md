---
decisionKey: "928de8ebdb328c1661208c53b368e08c7adb247a0a244b7fdef16318ea1ae99a"
language: "zh-CN"
title: "未来策略近似法提升离线强化学习在LLM推理中的表现"
summary: "一种名为未来策略近似（FPA）的新方法通过解决梯度纠缠问题，在多个数学和代码基准上优于现有离线强化学习基线，同时以较低的GPU成本达到与在线方法相当的性能。"
publishedAt: "2026-08-20T14:09:19.508Z"
score: 0.82
topics:
  - "Reinforcement Learning"
  - "Large Language Models"
  - "Offline RL"
topicIds:
  - "reinforcement-learning-pvp23c"
  - "large-language-models-1okubv8"
  - "offline-rl-o3tn7a"
sourceUrls:
  - "https://arxiv.org/abs/2509.19893"
---

离线强化学习旨在从固定数据集中学习策略，无需与环境交互。在大型语言模型（LLM）的推理任务中，长程推理轨迹常导致梯度纠缠问题，即不同时间步的梯度相互干扰，影响优化效果。FPA提出了一种新的离线策略梯度方法，通过对数空间外推估计未来策略，并据此重新加权梯度，以缓解该问题。

实验表明，FPA在三种模型、七个数学推理基准和三个代码生成基准上，均优于DPO、RPO、KTO等强离线基线，以及普通离线强化学习方法。此外，FPA的准确率与GRPO、DAPO等最先进的在线强化学习方法相当，但所需的GPU时间远少于这些方法。

该论文为arXiv预印本，尚未经过同行评审，因此上述结果应视为初步成果，其有效性和泛化能力有待进一步验证。
