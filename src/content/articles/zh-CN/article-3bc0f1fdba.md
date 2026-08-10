---
decisionKey: "3bc0f1fdba4ff9df6dda8f569b7bacdd219b84e34a12ea6765eb6c3790d8d8f2"
language: "zh-CN"
title: "帕累托前沿评估显示认证训练基线存在欠调优"
summary: "该研究提出用自动化多目标超参数搜索比较认证训练方法在自然准确率与认证准确率之间的帕累托前沿。这一评估框架会改变哪些配置显得更优，并表明以往的方法排名建立在欠调优的设置上。"
publishedAt: "2026-08-10T15:13:40.453Z"
score: 0.85
topics:
  - "Certified Training"
  - "Adversarial Robustness"
  - "Model Evaluation"
topicIds:
  - "certified-training-ptfn4c"
  - "adversarial-robustness-1dsh08l"
  - "model-evaluation-rkej78"
sourceUrls:
  - "https://arxiv.org/abs/2606.02134"
---

论文《Rethinking Evaluation Paradigms in IBP-based Certified Training》提出，通过比较各方法在自然准确率与认证准确率权衡上的帕累托前沿来评估认证训练方法。为构建这一比较，论文使用自动化多目标超参数优化，为每种方法寻找帕累托最优配置。

帕累托前沿分析发现，此前报告的配置存在明显的欠调优。优化后的配置表现更优，并为认证训练设立了新的最先进水平。作者称这是首次对认证训练方法进行全面的多目标比较，并指出先前的方法改进并不像假设的那样显著；比较还揭示了此前未被报告的性能互补关系。

摘要未说明数据集、模型架构、对比的基线方法、超参数搜索预算或统计显著性度量。缺乏这些细节时，所报告收益的程度和可推广性无法被充分评估，结论的普适性也仍是开放问题。
