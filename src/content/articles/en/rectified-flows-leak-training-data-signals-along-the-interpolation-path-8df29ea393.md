---
decisionKey: "8df29ea393ed7e2c6c7e0f49581e0fe62e0952efb18c7b76761285fa1865d366"
language: "en"
title: "Rectified Flows leak training-data signals along the interpolation path"
summary: "A theoretical and empirical study shows that Rectified Flow models leave a bell-shaped membership signal along the interpolation path, with a closed-form peak location under Gaussian assumptions. The finding is validated on audio and images and is used in a proof-of-concept membership inference attack."
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

This study examines Rectified Flow training and compares how training and test data are reconstructed along the interpolation path. The authors report that a gap between reconstructions of training and test samples appears along the path, accumulates during training, and emerges while validation metrics remain stable.

Making the interpolation step explicit, the membership signal is bell-shaped as a function of λ, and under Gaussian assumptions its peak location can be derived in closed form. The authors validate this shape on audio and image data, with the peak prediction holding when the Gaussian assumptions are satisfied. Using this λ-resolved signal, they build a proof-of-concept Membership Inference Attack that distinguishes training-set members from non-members.

The available evidence does not include quantitative attack performance or the detailed experimental protocol, so the practical strength of the Membership Inference Attack is not assessed here. The closed-form peak location also depends on the Gaussian assumptions being satisfied.
