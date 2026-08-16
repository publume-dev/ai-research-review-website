---
decisionKey: "222da4cf9b6e46187123ad213542d26bdd1cc733b01d2d85742174245f0ceba0"
language: "en"
title: "SOOPER: Safe Exploration via Conservative Policy Priors"
summary: "SOOPER balances optimistic exploration with pessimistic fallback using probabilistic dynamics models, achieving safety and convergence guarantees in reinforcement learning with superior performance on benchmarks and hardware."
publishedAt: "2026-08-16T03:16:05.622Z"
score: 0.85
topics:
  - "Reinforcement Learning"
  - "Safe Exploration"
topicIds:
  - "reinforcement-learning-pvp23c"
  - "safe-exploration-13y8hf9"
sourceUrls:
  - "https://arxiv.org/abs/2601.19612"
---

Safe reinforcement learning aims to train agents to avoid dangerous behaviors during exploration. SOOPER uses probabilistic dynamics models to model environment uncertainty and leverages a conservative policy prior as a safety fallback. The study includes experiments on multiple safe RL benchmarks and real-world hardware.

SOOPER's core mechanism switches between optimistic exploration and pessimistic fallback: when model uncertainty is low, it explores optimistically; otherwise, it falls back to a conservative policy. The method provides theoretical guarantees, including safety throughout learning and convergence to an optimal policy by bounding cumulative regret. Experiments demonstrate that SOOPER is scalable and outperforms state-of-the-art methods on key safe RL benchmarks and real hardware.

The abstract mentions theoretical guarantees, but the specific conditions and assumptions are not detailed. Additionally, the paper is a preprint and has not undergone peer review.
