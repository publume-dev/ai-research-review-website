---
decisionKey: "ab0c180d2e0139244cd5f5b7b96c52e4b408017ddb272366cec6867a6f94ef11"
language: "zh-CN"
title: "联邦参数高效框架实现隐私保护的多机构医学大模型适配"
summary: "新提出的Fed-MedLoRA框架仅传输低秩适配器而非完整模型权重，并引入自适应聚合以应对跨机构数据异质性，在五个独立患者队列的临床信息抽取中持续改善性能。"
publishedAt: "2026-08-15T03:03:56.055Z"
score: 0.85
topics:
  - "Federated Learning"
  - "Medical AI"
  - "Large Language Models"
topicIds:
  - "federated-learning-tztnd3"
  - "medical-ai-112vis2"
  - "large-language-models-1okubv8"
sourceUrls:
  - "https://arxiv.org/abs/2601.22124"
---

该研究针对医学领域大语言模型（LLM）在多机构场景下的适配难题，提出参数高效的联邦学习框架Fed-MedLoRA及其增强版Fed-MedLoRA+。其核心设计是仅传输低秩适配器而非完整模型权重，Fed-MedLoRA+进一步加入自适应聚合以处理跨机构数据异质性。

在包含42,198个实体和41,570个关系的五个独立患者队列上，该框架用于临床信息抽取任务，相比零样本、微调LLM、领域专用BERT模型及联邦基线，持续提升了抽取性能和泛化能力。在耶鲁纽黑文健康系统的真实临床笔记案例研究中，该框架在低资源新站点部署下表现出强性能。

该论文为预印本（arXiv版本3），尽管标注'刚被接收'可能暗示同行评审，但未明确说明。摘要中未提供具体的效应量和基准差异数值。
