---
decisionKey: "0bd5e9dbf90ddcee0edc9c3886471e40dcc2350edbefaa7d993a77c92e49f2e8"
language: "zh-CN"
title: "首个可扩展的步态基础模型：自监督预训练框架"
summary: "研究者提出FoundationGait，一种可扩展的自监督预训练框架，在12个公共步态数据集上训练超过200万条行走序列，实现跨数据集与多任务的零样本性能提升。"
publishedAt: "2026-08-21T14:06:18.549Z"
score: 0.92
topics:
  - "Computer Vision"
  - "Foundation Models"
  - "Gait Recognition"
topicIds:
  - "computer-vision-ykrxu8"
  - "foundation-models-29zx6m"
  - "gait-recognition-19d2ozz"
sourceUrls:
  - "https://arxiv.org/abs/2512.00691"
---

步态识别是计算机视觉中用于身份识别的生物特征技术，但现有方法受限于特定数据集和任务，泛化能力不足。为解决该问题，研究人员开发了FoundationGait，据称是首个可扩展的自监督预训练框架。其最大版本参数接近1.3亿，预训练数据来自12个公共步态数据集，包含超过200万条行走序列。

在零样本评估中，FoundationGait在Gait3D数据集（包含1000个测试对象）上达到48.0%的rank-1准确率，在OU-MVLP数据集（包含超过5000个测试对象）上达到64.5%。此外，它在多种步态数据集、不同条件（如跨视角、跨场景）、不同任务（包括人类身份识别、脊柱侧弯筛查、抑郁预测、属性估计）中表现稳定，无论是否进行微调均有效。

该论文目前是预印本，尚未经过同行评审。摘要中未提供与现有方法的详细对比或实验设置，因此其优于现有方法的结论尚未被完全量化。
