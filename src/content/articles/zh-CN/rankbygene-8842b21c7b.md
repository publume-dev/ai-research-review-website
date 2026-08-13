---
decisionKey: "8842b21c7b47145dae7418ed465dbd76810bf861d3036b2e8bd6ecd953f0f401"
language: "zh-CN"
title: "RankByGene：基于跨模态排序一致性的基因引导组织病理学表示学习"
summary: "RankByGene 提出了一种基于排序的跨模态对齐方法，用于空间转录组学与组织病理学数据，并通过自监督知识蒸馏稳定图像表示，在七个公共数据集上提升了预测性能。该论文已被 IEEE 医学影像汇刊（TMI）接收。"
publishedAt: "2026-08-13T05:50:28.271Z"
score: 0.82
topics:
  - "AI in Medicine"
  - "Representation Learning"
  - "Computer Vision"
topicIds:
  - "ai-in-medicine-fz6vbm"
  - "representation-learning-1upc2hm"
  - "computer-vision-ykrxu8"
sourceUrls:
  - "https://arxiv.org/abs/2411.15076"
---

RankByGene 是一种用于组织病理学图像与基因表达数据对齐的表示学习方法。该方法基于跨模态排序一致性，并采用教师-学生架构的自监督知识蒸馏作为模态内稳定性正则化器，以防止跨模态对齐过程中图像表示漂移。论文已被 IEEE 医学影像汇刊（TMI）2026 年接收，代码已公开。

在七个公共数据集上的实验表明，RankByGene 在基因表达预测、切片级分类和生存分析等任务中，相比现有方法实现了改进的对齐和预测性能。

摘要未提供定量效应量或基准差异，仅作了定性改进声明。此外，具体数据集、基线比较和评估协议的细节在摘要中未作描述。
