---
decisionKey: "3237cb40a47022da8375f318341de41c28dc6db9fb5c4a7d9a66c3163b8f5bcf"
language: "zh-CN"
title: "语言模型作为形式化工具在约束满足问题上的实际表现：一项系统评估"
summary: "一项新研究系统评估了大型语言模型作为约束满足问题形式化工具的表现，发现在24种模型与数据集组合中，有15种组合下其效果不如直接作为求解器使用。"
publishedAt: "2026-08-13T05:50:28.271Z"
score: 0.85
topics:
  - "Language Models"
  - "Symbolic Reasoning"
  - "Constraint Satisfaction"
topicIds:
  - "language-models-5wxasf"
  - "symbolic-reasoning-61y9g1"
  - "constraint-satisfaction-17a6356"
sourceUrls:
  - "https://arxiv.org/abs/2505.13252"
---

该研究针对将大型语言模型（LLM）用作形式化工具（LLM-as-formalizer）的做法进行了系统检验，即在约束满足问题中让模型生成形式化表述而非直接求解。评估覆盖了4个基准、6种LLM和2种形式语言。

研究发现，在全部24种模型与数据集的组合中，LLM作为形式化工具（LLM-as-formalizer）在15种组合下表现不如LLM作为直接求解器（LLM-as-solver）。这一结果表明，当前LLM在生成形式化约束方面并未稳定优于直接求解，且随着问题复杂度提升，其形式化表现可能进一步受限。

该研究的摘要未明确列出具体使用的基准、模型和形式语言，也未说明性能差异的大小。因此，上述发现的具体适用范围和效应量尚不清楚。
