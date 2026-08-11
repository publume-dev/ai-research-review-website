---
decisionKey: "6dcd31fa6e20bf47faded18a831462b18e2136724d4ff0747f6ddd27e49075ee"
language: "zh-CN"
title: "基于物理模糊模型的清晰可驱动高斯虚拟人重建"
summary: "一篇CVPR 2026论文提出直接从模糊多视角视频重建清晰、可驱动的3D高斯虚拟人，并基于物理模糊模型将虚拟人与运动参数联合优化。"
publishedAt: "2026-08-11T11:27:48.780Z"
score: 0.82
topics:
  - "Computer Vision"
  - "3D Human Avatars"
  - "Gaussian Splatting"
  - "Deblurring"
topicIds:
  - "computer-vision-ykrxu8"
  - "3d-human-avatars-18bay79"
  - "gaussian-splatting-1vr3z2e"
  - "deblurring-v4ho39"
sourceUrls:
  - "https://arxiv.org/abs/2411.16758"
---

多视角视频中的运动模糊是人像虚拟人重建中的常见问题，但既有方法通常假设输入帧清晰。这项研究直接面向模糊多视角视频，目标是从中重建清晰的3D人体高斯虚拟人。论文已被CVPR 2026接收。

该方法的核心是引入3D感知的、基于物理的运动模糊模型，并结合3D人体运动模型；从粗略初始化出发，虚拟人表示和运动参数被联合优化。为评估效果，作者在合成数据集以及由360度同步混合曝光相机系统采集的真实数据集上建立基准。

公开摘要未报告定量基准差异或消融结果。因此，该方法相对基线的改进幅度，以及模糊模型与运动模型各自的独立贡献，无法从该来源单独评估。
