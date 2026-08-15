---
decisionKey: "b025f51e39d291de5b9ddc4fcd3d00b277ae90caf58de619032097eebf314a59"
language: "en"
title: "Optimizing Likelihoods via Mutual Information: Bridging Simulation-Based Inference and Bayesian Optimal Experimental Design"
summary: "The new research links simulation-based inference and Bayesian optimal experimental design through mutual information bounds, proposing SBI-BOED, which jointly optimizes experimental designs and inference functions, showing notable improvements on real-world simulators in epidemiology and biology."
publishedAt: "2026-08-15T03:03:56.055Z"
score: 0.86
topics:
  - "Simulation-Based Inference"
  - "Bayesian Optimal Experimental Design"
  - "Amortized Inference"
topicIds:
  - "simulation-based-inference-177tfxr"
  - "bayesian-optimal-experimental-design-1b1qgej"
  - "amortized-inference-12zk5wv"
sourceUrls:
  - "https://arxiv.org/abs/2502.08004"
---

Simulation-based inference (SBI) is a method for inference through simulators, while Bayesian optimal experimental design (BOED) aims to select optimal experimental designs to maximize information gain. The study demonstrates a link via mutual information bounds between SBI and stochastic gradient-based variational inference methods, permitting BOED to be used in SBI applications as SBI-BOED.

The proposed SBI-BOED approach allows simultaneous optimization of experimental designs and amortized inference functions. The method is evaluated on SBI-based models in real-world simulators in epidemiology and biology, showing notable improvements in inference. The paper also evaluates pitfalls of naive design optimization in a standard SBI task and demonstrates the utility of a well-chosen design distribution in BOED.

The abstract does not provide quantitative details of the improvements (e.g., effect sizes, benchmark deltas) or specific limitations. The paper is accepted at UAI 2026, which is in the future relative to the arXiv version date; the actual peer-reviewed publication may not yet be available.
