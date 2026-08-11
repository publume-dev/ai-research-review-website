---
decisionKey: "4e36fb6267dd1840be260fb8a7a44c25f750bb98ed326b61667d071f6f8aa3cd"
language: "en"
title: "An Exact High-dimensional Theory of Iterative Pseudo-label Self-training"
summary: "A theory paper accepted at JMLR characterizes when iterative self-training with pseudo-labels helps ridge-regularized linear classifiers on Gaussian mixtures and shows how to counter label imbalance. The result moves a widely used heuristic onto a rigorous asymptotic footing."
publishedAt: "2026-08-11T18:46:48.986Z"
score: 0.82
topics:
  - "Self-training Theory"
  - "Semi-supervised Learning"
  - "High-dimensional Statistics"
topicIds:
  - "self-training-theory-1xblht9"
  - "semi-supervised-learning-1miumji"
  - "high-dimensional-statistics-18910x4"
sourceUrls:
  - "https://arxiv.org/abs/2205.07739"
---

Self-training is a common semi-supervised technique, but its behavior is not fully understood. This paper gives an exact asymptotic analysis of iterative self-training for ridge-regularized convex-loss linear classifiers on binary Gaussian mixture data, in the regime where input dimension and data size diverge proportionally. The camera-ready arXiv version reports acceptance at the Journal of Machine Learning Research (JMLR).

The analysis distinguishes two regimes. With few iterations, self-training improves generalization by fitting relatively reliable pseudo-labels and making large parameter updates; with many iterations, it gradually improves the classification-plane direction through small soft-label updates and small regularization. Under label imbalance, self-training underperforms supervised learning with true labels. The paper proposes two heuristics that make self-training nearly match supervised-learning performance even when the label imbalance is significant.

The result is asymptotic and restricted to binary Gaussian mixture models. The abstract does not provide experimental evidence on real datasets, so practical impact outside this setting remains to be demonstrated.
