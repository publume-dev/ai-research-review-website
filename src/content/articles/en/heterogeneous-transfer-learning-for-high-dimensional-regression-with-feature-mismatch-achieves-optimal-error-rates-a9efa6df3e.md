---
decisionKey: "a9efa6df3ede34d04002dcecb99e48df700c8b1baf7bce2ac1998485c7aa9d98"
language: "en"
title: "Heterogeneous transfer learning for high-dimensional regression with feature mismatch achieves optimal error rates"
summary: "A new method handles different feature sets between source and target domains in high-dimensional regression transfer learning by learning a feature map and imputing missing features, with theoretical optimal error bounds."
publishedAt: "2026-08-13T05:50:28.271Z"
score: 0.85
topics:
  - "Transfer Learning"
  - "High-Dimensional Regression"
topicIds:
  - "transfer-learning-lz7sfo"
  - "high-dimensional-regression-1re5qvm"
sourceUrls:
  - "https://arxiv.org/abs/2412.18081"
---

This research addresses transfer learning in high-dimensional regression, where traditional methods typically assume matching feature sets between source and target domains. In real scenarios, the source may contain features absent in the target, making direct transfer inefficient. The authors propose a heterogeneous transfer learning method that learns a feature map and imputes missing features in the target domain to leverage all source information.

The method provides upper bounds on estimation and prediction errors, and establishes matching minimax lower bounds, proving optimal convergence rates. Theoretical analysis shows that, compared to homogeneous transfer learning that discards unavailable features, the proposed approach can achieve a smaller error rate.

The paper is a preprint and has not undergone peer review. The abstract presents only theoretical results without experimental validation on real-world datasets, so practical performance remains to be verified.
