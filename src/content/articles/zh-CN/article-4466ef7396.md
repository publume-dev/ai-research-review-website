---
decisionKey: "4466ef739696845da1f2bc8663c35c85eee24f30b26dec30adcbb81d1ec235ab"
language: "zh-CN"
title: "数字孪生的因果证伪：基于败血症案例研究的可靠方法"
summary: "一篇被《机器学习研究杂志》（JMLR）接收的论文为数字孪生定义了一种精确的因果正确性概念，并提出一种仅凭观测轨迹即可执行的证伪流程。该方法在基于MIMIC-III数据的败血症建模中得到应用。"
publishedAt: "2026-08-11T18:46:48.986Z"
score: 0.9
topics:
  - "Causal Inference"
  - "Digital Twins"
  - "Model Validation"
topicIds:
  - "causal-inference-1fgx8yv"
  - "digital-twins-v0rpz0"
  - "model-validation-2gitwt"
sourceUrls:
  - "https://arxiv.org/abs/2301.07210"
---

数字孪生是用于映射真实系统的计算模型，但在混杂因素存在时验证模型是否正确并不简单。论文提出一种精确的因果正确性定义，为数字孪生验证提供了形式化目标。该工作已被《机器学习研究杂志》（JMLR）接收发表。

该证伪流程只需一组独立同分布（i.i.d.）的观测轨迹数据集，并且按论文所述即使在混杂情况下依然保持可靠性。在案例研究中，作者使用MIMIC-III重症监护数据集，将方法应用于Pulse Physiology Engine中的败血症建模。

论文摘要未报告量化评估指标，因此该方法与现有验证方法相比的实际性能尚未说明。
