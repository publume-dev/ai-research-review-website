---
decisionKey: "6f23c2d1d004d643fde7adb8e1e62ea787ef189975ee490216bd89a0dda0961e"
language: "zh-CN"
title: "仅用加速度计的车辆速度估计：CarSpeedNet 模型与长窗口效果"
summary: "CarSpeedNet 仅利用智能手机三轴加速度数据估计车辆速度，无需陀螺仪等额外输入。实验表明，将输入窗口从 1 秒增至 4 秒，可将均方根误差从 2.9 m/s 降至 1.8 m/s。"
publishedAt: "2026-08-21T14:06:18.549Z"
score: 0.85
topics:
  - "Machine Learning"
  - "Applied ML"
topicIds:
  - "machine-learning-168tuwc"
  - "applied-ml-1tlxfzz"
sourceUrls:
  - "https://arxiv.org/abs/2401.07468"
---

CarSpeedNet 是一种基于学习的模型，用于从智能手机的三轴加速度计数据估计车辆速度，推理时无需陀螺仪、轮速计、车辆总线或定位输入。该模型参数量为 178,169，32 位权重约占 0.68 MiB。

在 13.2 小时的真实道路驾驶数据实验中，将输入窗口从 1 秒增加到 4 秒后，在 0.5 小时的留出测试集上，均方根误差从 2.9 m/s 降至 1.8 m/s，平均绝对误差从 1.3 m/s 降至 0.72 m/s。该结果表明，更长的时序上下文有助于提升速度估计的准确性。

该论文目前为预印本，正在审稿中，结果尚未经过同行评审。此外，评估基于单一驾驶会话的数据集，其对多样条件的泛化能力尚未明确。
