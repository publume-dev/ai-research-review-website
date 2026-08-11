---
decisionKey: "c6da97eef84925f0d68afb7616e631e3a2e492f007dc03277ff6e33cb96c780b"
language: "zh-CN"
title: "AQUA20基准发布：面向水下物种分类"
summary: "AQUA20基准数据集包含8,171幅水下图像，覆盖20个海洋物种，并提供了13个深度学习模型的评测结果，其中ConvNeXt取得了最佳准确率。该基准针对光照、浑浊度和遮挡等实际挑战而设计。"
publishedAt: "2026-08-11T18:46:48.986Z"
score: 0.86
topics:
  - "Computer Vision"
  - "Benchmark Dataset"
  - "Underwater Species Classification"
topicIds:
  - "computer-vision-ykrxu8"
  - "benchmark-dataset-tydhb8"
  - "underwater-species-classification-xrneou"
sourceUrls:
  - "https://arxiv.org/abs/2506.17455"
---

作者将AQUA20作为用于苛刻水下视觉条件下的物种分类基准数据集。该数据集包含8,171幅图像，覆盖20个海洋物种，旨在反映光照、浑浊度和遮挡等问题。研究比较了13种深度学习架构，包括轻量级CNN（SqueezeNet、MobileNetV2）和基于Transformer的模型（ViT、ConvNeXt）。该来源是arXiv预印本，带有期刊引用，但未提供完整的同行评审细节。

在AQUA20上的评测中，ConvNeXt取得了最佳Top-3准确率（98.82%）、Top-1准确率（90.69%）和整体F1值（88.92%）。论文还报告了GRAD-CAM和LIME可解释性分析，以解释模型的优势与失败模式。

摘要未提供AQUA20的逐类别图像数量、图像来源或标注质量评估。评测指标以聚合结果报告，没有置信区间或显著性检验，因此ConvNeXt相对于其他模型的性能差距大小尚未得到统计量化。
