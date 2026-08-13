---
decisionKey: "023a98096d79526db38077335ff3b91a40fefef367f6eaae13d83afad7ba21ac"
language: "en"
title: "A New First-Order Meta-Learning Algorithm with Convergence Guarantees"
summary: "FO-B-MAML is a new first-order meta-learning algorithm derived from a bi-level optimization perspective, converging to a stationary point of the meta-objective, and introducing improved finite-difference gradient estimators with a bias rate of O(delta^{2/3}). It achieves high accuracy close to second-order MAML while bypassing the activation bottleneck and maintaining a flat memory footprint on deep, activation-heavy CNNs and Transformers."
publishedAt: "2026-08-13T05:50:28.271Z"
score: 0.85
topics:
  - "Meta-Learning"
  - "Optimization"
topicIds:
  - "meta-learning-1l2n8j1"
  - "optimization-wc4i1w"
sourceUrls:
  - "https://arxiv.org/abs/2409.03682"
---

FO-B-MAML is a first-order variant of MAML derived from a bi-level optimization perspective, introducing a new expression of the meta-gradient as the derivative of the solution of a perturbed optimization problem. Existing first-order methods like FO-MAML and Reptile suffer from irreducible bias.

FO-B-MAML converges to a stationary point of the meta-objective, unlike existing first-order methods that suffer from irreducible bias. The symmetric estimator achieves an improved bias rate of O(delta^{2/3}), strictly enhancing previous first-order theory. The paper also shows that the MAML objective violates standard smoothness assumptions, with its smoothness constant growing with the norm of the meta-gradient, justifying the use of normalized or clipped-gradient methods (SNGDM) over vanilla gradient descent. Empirically, FO-B-MAML achieves high accuracy, closely following second-order MAML performance, while bypassing the 'activation bottleneck' and maintaining a flat memory footprint when scaling to deep, activation-heavy CNNs and Transformers.

The research is based on an arXiv preprint and has not been peer-reviewed. The paper does not provide specific datasets or benchmarks tested, nor quantitative performance metrics compared to existing methods, such as exact accuracy numbers or memory footprint data. Furthermore, the generalizability of the practical benefits (e.g., across different task families) remains unclear.
