---
decisionKey: "928de8ebdb328c1661208c53b368e08c7adb247a0a244b7fdef16318ea1ae99a"
language: "en"
title: "Future Policy Approximation for Offline Reinforcement Learning in LLM Reasoning"
summary: "A new method called Future Policy Approximation (FPA) improves over existing offline reinforcement learning baselines on math and code benchmarks by addressing gradient entanglement, while achieving performance comparable to online methods at lower GPU cost."
publishedAt: "2026-08-20T14:09:19.508Z"
score: 0.82
topics:
  - "Reinforcement Learning"
  - "Large Language Models"
  - "Offline RL"
topicIds:
  - "reinforcement-learning-pvp23c"
  - "large-language-models-1okubv8"
  - "offline-rl-o3tn7a"
sourceUrls:
  - "https://arxiv.org/abs/2509.19893"
---

Offline reinforcement learning aims to learn policies from fixed datasets without interacting with the environment. In large language model (LLM) reasoning tasks, long-horizon trajectories often lead to gradient entanglement, where gradients at different time steps interfere with each other, hindering optimization. FPA proposes a new offline policy gradient method that estimates a future policy via logit-space extrapolation and reweights gradients accordingly to mitigate this issue.

Experiments show that FPA consistently outperforms strong offline baselines such as DPO, RPO, and KTO, as well as vanilla offline reinforcement learning, across three models, seven mathematical reasoning benchmarks, and three code generation benchmarks. Additionally, FPA achieves accuracy comparable to state-of-the-art online reinforcement learning methods like GRPO and DAPO, but with significantly fewer GPU hours.

The paper is an arXiv preprint and has not been peer-reviewed yet; therefore, the results should be treated as preliminary, and their validity and generalizability require further verification.
