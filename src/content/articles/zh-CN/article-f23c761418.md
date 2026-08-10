---
decisionKey: "f23c76141816b76e1803b225687bdabd62471ac091e4d97992d7211bd2af58b7"
language: "zh-CN"
title: "配置调优替代模型评估：研究提出超越精度的适应度景观效用理论"
summary: "配置调优需要替代模型来避免逐一运行配置；这项研究提出根据适应度景观判断替代模型是否真正有用，并报告其 Model4Tune 预测器在 79%–82% 的案例中显著优于随机猜测。"
publishedAt: "2026-08-10T15:13:40.453Z"
score: 0.82
topics:
  - "Configuration Tuning"
  - "Surrogate Models"
  - "Fitness Landscape Analysis"
topicIds:
  - "configuration-tuning-198j9b2"
  - "surrogate-models-19m90l5"
  - "fitness-landscape-analysis-tex3tw"
sourceUrls:
  - "https://arxiv.org/abs/2509.21945"
---

配置调优用替代模型估计未尝试配置的性能，但预测精度高并不等于对调优过程有用。论文提出一种基于适应度景观分析的理论，用于评估替代模型在配置调优中的有用性，而不是只看精度。arXiv 摘要说明该工作已被 TOSEM 接收。

作者还提出 Model4Tune，一个用于估计在未见过的系统上哪些模型–调优器组合最优的预测工具，无需昂贵的调优器剖析。在最多包含 27,000 个案例的实证研究中，Model4Tune 在 79%–82% 的案例中显著优于随机猜测。

本次评估仅基于 arXiv 摘要，因此详细的实验设计、所覆盖的系统与调优器、性能指标、置信区间和可复现性尚未核实。摘要中的评论注明论文被 TOSEM 接收，但 arXiv 页面没有提供完整审稿历史。
