---
decisionKey: "fb099725fffc11307359480c1e3fb4ae662e6f4d2437888ff5166e4b45856304"
language: "zh-CN"
title: "MiraMind与Mindora：为心理健康推理建立可靠性基准"
summary: "“MiraMind”是一个面向心理健康推理的新基准，与作者的“Mindora”模型一起，将LLM评估的重点从单纯的答案准确率转向可靠性。论文记录了一个“克制差距”：模型判断可能比证据所支持的更确定或更具体。"
publishedAt: "2026-08-11T18:46:48.986Z"
score: 0.85
topics:
  - "Mental Health Reasoning"
  - "LLM Benchmarking"
  - "Reasoning Reliability"
topicIds:
  - "mental-health-reasoning-cvrsv6"
  - "llm-benchmarking-162krip"
  - "reasoning-reliability-7enqu3"
sourceUrls:
  - "https://arxiv.org/abs/2512.09636"
---

论文引入了MiraMind基准，用于评估大语言模型在心理健康推理中的表现，重点考察超越答案准确率的可靠性。该基准覆盖六个任务族——评估、诊断、干预、抽象和验证——共13个数据集。为改进从证据到判断的转换，作者训练了80亿参数的Mindora模型，采用了困难样本监督、结构化轨迹重写和一致性感知优化。由于论文是未经同行评审的arXiv预印本，基准的有效性和模型结论目前依赖作者自己的评估。

作者在20个大语言模型上评估MiraMind后发现了“克制差距”：模型判断可能比有限证据所支持的结果更具体或更确定。Mindora在MiraMind上取得了最佳平均排名，并在全部六类任务上超过其骨干模型，同时生成了比骨干模型更均衡的推理轨迹。

摘要没有给出定量效应量、13个数据集的名称或20个大语言模型的具体名单，因此Mindora改进的实际意义尚不能完全评估。摘要也没有定义轨迹层面的指标——可用性、逻辑结构、信息贡献——这使得可靠性提升难以解释。
