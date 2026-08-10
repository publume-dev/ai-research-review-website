---
decisionKey: "556a55fe17bb25be839fcf1177403061668d0d5763c8f45ce0f3f78000a91129"
language: "zh-CN"
title: "上下文示例会抑制大语言模型对科学知识的调用"
summary: "一项研究发现，添加上下文示例会让大语言模型更少依赖预训练的科学领域知识，转向基于经验的模式拟合；即使示例与待解问题由同一公式生成，这种偏移仍会出现。该效应对准确性的影响并不一致，因此添加示例的实际收益并不能保证。"
publishedAt: "2026-08-10T15:13:40.453Z"
score: 0.85
topics:
  - "In-Context Learning"
  - "Large Language Models"
  - "Scientific Reasoning"
  - "Knowledge Recall"
topicIds:
  - "in-context-learning-1ggksgq"
  - "large-language-models-1okubv8"
  - "scientific-reasoning-1mn3lwk"
  - "knowledge-recall-1cajhqs"
sourceUrls:
  - "https://arxiv.org/abs/2604.27540"
---

这项研究在 60 个潜在结构恢复任务、6,000 次试验、4 个模型和 5 个科学领域中考察了上下文示例如何改变大语言模型的行为。关键条件是，部分示例与测试问题由同一公式生成，以观察模型是否会从知识驱动转向经验拟合。

在全部条件中，提供上下文示例都使模型对预训练科学知识的依赖降低，并转向经验模式拟合。准确性影响并不一致：有时下降，有时不变，有时看似提升；但研究者报告，所有情况下模型的推理都偏离了知识驱动的方式。

该摘要只报告了汇总结果，没有说明参与测试的四个模型具体是哪些，也没有给出效应量；因此，实际部署中的影响大小尚未量化。
