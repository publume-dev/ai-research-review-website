---
decisionKey: "9aea5ab13391e7d1e494025127c9b7213d4b7d1d1c76f8e17543580b9507c42d"
language: "en"
title: "Weak-to-Strong Generalization via Bregman Bias-Variance Decomposition"
summary: "A new theory decomposes the risk gap in weak-to-strong generalization using Bregman divergence, removing the need for convexity in the student hypothesis class and suggesting improved strategies for squared and cross-entropy losses."
publishedAt: "2026-08-20T14:09:19.508Z"
score: 0.82
topics:
  - "Weak-to-Strong Generalization"
  - "Bias-Variance Decomposition"
  - "Bregman Divergence"
  - "Machine Learning Theory"
topicIds:
  - "weak-to-strong-generalization-1muolft"
  - "bias-variance-decomposition-llek5b"
  - "bregman-divergence-16qw15r"
  - "machine-learning-theory-r9f4fp"
sourceUrls:
  - "https://arxiv.org/abs/2505.24313"
---

Weak-to-strong generalization studies how to train a stronger model using supervision from a weaker one. This paper proposes a generalized bias-variance decomposition under Bregman divergence to characterize the population risk gap between student and teacher models.

For squared loss, the paper provides a sufficient condition under which the student converges to the posterior mean teacher, and increasing student model size can ensure convergence. For cross-entropy loss, the analysis suggests that lowering the entropy of the student's predictive distribution can promote weak-to-strong generalization, and reverse cross-entropy is less sensitive to teacher predictive uncertainty than forward cross-entropy. Empirical results show that incorporating reverse cross-entropy consistently improves student performance in weak-to-strong settings.

The abstract describes theory and empirical verification but does not provide specific quantitative results or dataset details, which are typically needed to fully assess practical significance.
