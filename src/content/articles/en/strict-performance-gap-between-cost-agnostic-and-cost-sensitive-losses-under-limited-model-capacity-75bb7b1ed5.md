---
decisionKey: "75bb7b1ed506422acf597cac1e256dc1fb7245eef1830321955d9c53d7463b21"
language: "en"
title: "Strict Performance Gap Between Cost-Agnostic and Cost-Sensitive Losses Under Limited Model Capacity"
summary: "This study proves via H-consistency theory that under limited model capacity, a model trained with a cost-agnostic objective may have strictly worse performance than one trained with a cost-sensitive loss, even when the decision boundary is recoverable."
publishedAt: "2026-08-20T14:09:19.508Z"
score: 0.78
topics:
  - "Machine Learning Theory"
  - "Loss Functions"
topicIds:
  - "machine-learning-theory-r9f4fp"
  - "loss-functions-2kad6r"
sourceUrls:
  - "https://arxiv.org/abs/2502.19522"
---

The research contrasts two types of loss functions: cost-agnostic objectives that ignore misclassification costs, and cost-sensitive losses that account for them. The theoretical analysis focuses on whether threshold post-processing can always compensate for the lack of cost sensitivity when model capacity is limited.

The paper shows that when a hypothesis class can recover the optimal decision boundary but its optimal cost-agnostic hypothesis is misaligned with that boundary, a model trained with a cost-agnostic objective strictly underperforms one optimized for a cost-sensitive loss, even after threshold adjustment. A simple example demonstrates the plausibility of this setting. Under assumptions that are hard to verify in practice, the paper further demonstrates the gap generally exists on UCI classification datasets, particularly with very simple models.

The empirical demonstration relies on assumptions that are difficult to verify in practice, and the paper does not report precise effect sizes or benchmark deltas. Therefore, the generality of the conclusion requires further study under more verifiable conditions.
