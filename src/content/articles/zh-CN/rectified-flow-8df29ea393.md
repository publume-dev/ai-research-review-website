---
decisionKey: "8df29ea393ed7e2c6c7e0f49581e0fe62e0952efb18c7b76761285fa1865d366"
language: "zh-CN"
title: "Rectified Flow 沿插值路径泄露训练数据成员信号"
summary: "一项理论和实验研究显示，Rectified Flow 模型会沿插值路径留下钟形的训练数据成员信号，且在高斯假设下该信号峰值位置有闭式解。该结果在音频和图像上得到验证，并被用于概念验证的成员推断攻击。"
publishedAt: "2026-08-10T15:13:40.453Z"
score: 0.86
topics:
  - "Generative Models"
  - "Membership Inference"
  - "Rectified Flows"
topicIds:
  - "generative-models-145h363"
  - "membership-inference-elz2q"
  - "rectified-flows-1e45ljr"
sourceUrls:
  - "https://arxiv.org/abs/2606.07271"
---

这项研究考察 Rectified Flow 训练，并沿插值路径比较训练数据与测试数据的重建结果。作者报告称，训练样本与测试样本的重建在插值路径上出现差距，该差距随训练累积，并在验证指标保持稳定时就已经出现。

将插值步骤显式化后，该信号随 λ 呈钟形变化；在高斯假设下，其峰值位置可得到闭式解。作者在音频和图像数据上验证了这一钟形结构，并在假设满足时观察到峰值预测成立。基于这种随 λ 变化的成员信号，他们实现了一个概念验证的成员推断攻击，能够区分训练集成员与非成员。

现有摘要证据未包含该成员推断攻击的定量表现和详细实验流程，因此无法据此评估其实用强度。闭式峰值位置的成立以高斯假设得到满足为前提。
