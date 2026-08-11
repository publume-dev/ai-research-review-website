---
decisionKey: "6dcd31fa6e20bf47faded18a831462b18e2136724d4ff0747f6ddd27e49075ee"
language: "en"
title: "Physics-Based Blur Model for Sharp Animatable Gaussian Avatars"
summary: "A CVPR 2026 paper reconstructs sharp, animatable 3D Gaussian avatars directly from blurry multi-view videos, with benchmarks on synthetic and real hybrid-exposure 360-degree captures."
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

Motion blur in multi-view video is a common issue for human avatar reconstruction, yet existing pipelines typically assume sharp input frames. This work targets direct reconstruction of sharp 3D human Gaussian avatars from such blurry captures. The paper is accepted at CVPR 2026.

The core contribution is a 3D-aware physics-based motion blur model combined with a 3D human motion model, enabling joint optimization of the avatar representation and motion parameters from a coarse initialization. For evaluation, the authors establish benchmarks on a synthetic dataset and a real-world dataset captured with a 360-degree synchronous hybrid-exposure camera system.

The published abstract reports no quantitative benchmark deltas or ablations. As a result, the size of the improvement over baselines and the individual contribution of the blur model versus the motion model cannot be independently assessed from this source.
