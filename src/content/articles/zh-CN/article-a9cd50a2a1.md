---
decisionKey: "a9cd50a2a1a158a75b8d82ada513c349217fb048086da7ed9a1fe77c7e831a6b"
language: "zh-CN"
title: "反事实模拟训练提升思维链忠实度"
summary: "反事实模拟训练（CST）通过奖励那些能在反事实输入上被模拟器准确预测输出的思维链，提升了大型语言模型的思维链忠实度；在最高 235B 参数的实验中，基于线索的监控准确率提升了 35 个百分点。该方法为获得更可信的推理痕迹提供了一条基于训练的路径，但预印本也明确指出了这些提升在哪些情况下无法泛化。"
publishedAt: "2026-08-10T15:13:40.453Z"
score: 0.85
topics:
  - "AI Research"
  - "Large Language Models"
  - "Chain-of-Thought Reasoning"
topicIds:
  - "ai-research-10iv84k"
  - "large-language-models-1okubv8"
  - "chain-of-thought-reasoning-myd2xs"
sourceUrls:
  - "https://arxiv.org/abs/2602.20710"
---

arXiv 预印本《反事实模拟训练用于思维链忠实度》提出了反事实模拟训练（CST）：通过奖励那些能让模拟器在反事实输入上准确预测模型输出的思维链（CoT），来提升 CoT 的忠实度。作者将 CST 应用于两种场景：基于线索反事实的 CoT 监控，以及基于通用模型反事实的反事实模拟。

在参数最高达 235B 的模型实验中，CST 将基于线索反事实的监控准确率提升了 35 个百分点，并将通用反事实上的可模拟性提升了 2 个百分点。作者报告称，CST 优于提示基线，并且用 LLM 重写不忠实的 CoT 比单独使用强化学习高效 5 倍。

摘要显示，CST 带来的忠实度提升并未泛化到劝阻性线索，且更大的模型并非开箱即用地展示出更忠实的 CoT，而是从 CST 中获益更多。摘要没有提供完整的方法细节、置信区间或统计显著性检验，因此效果量应参考完整同行评审论文。目前仅有这一份来源，尚无独立复现或其他外部报道。
