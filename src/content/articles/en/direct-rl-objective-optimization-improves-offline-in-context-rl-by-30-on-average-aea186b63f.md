---
decisionKey: "aea186b63fb2be2180f5f01e007a3eead96a1249a33ada2293eedd5f024490c3"
language: "en"
title: "Direct RL Objective Optimization Improves Offline In-Context RL by ~30% on Average"
summary: "A new study shows that optimizing RL objectives directly in offline in-context RL improves performance by approximately 30% on average over Algorithm Distillation (AD) across more than 150 GridWorld and MuJoCo datasets. In the XLand-MiniGrid environment, RL objectives doubled performance, and adding conservatism during value learning brought further gains."
publishedAt: "2026-08-15T03:03:56.055Z"
score: 0.88
topics:
  - "Reinforcement Learning"
  - "In-Context Learning"
  - "Offline RL"
topicIds:
  - "reinforcement-learning-pvp23c"
  - "in-context-learning-1ggksgq"
  - "offline-rl-o3tn7a"
sourceUrls:
  - "https://arxiv.org/abs/2502.17666"
---

Offline in-context reinforcement learning (ICRL) trains policies on offline data to adapt to new tasks via in-context learning. Algorithm Distillation (AD) is a common approach, but this study explores directly optimizing RL objectives instead.

On more than 150 datasets derived from GridWorld and MuJoCo environments, directly optimizing RL objectives improves performance by approximately 30% on average compared to AD. In the XLand-MiniGrid environment, RL objectives doubled AD's performance. Additionally, adding conservatism during value learning brings further improvements in almost all settings tested.

The paper is an arXiv preprint and has not been peer-reviewed. The abstract does not provide detailed experimental setup, baselines, or statistical significance, so results should be interpreted with caution.
