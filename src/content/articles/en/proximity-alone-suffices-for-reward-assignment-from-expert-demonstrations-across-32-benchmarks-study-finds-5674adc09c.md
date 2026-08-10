---
decisionKey: "5674adc09c720e3db4c89babd4ce6d1474a92446b035934e9b2d9200525b2e14"
language: "en"
title: "Proximity Alone Suffices for Reward Assignment From Expert Demonstrations Across 32 Benchmarks, Study Finds"
summary: "A study of reward assignment from expert demonstrations found that, across 32 benchmarks and three downstream RL algorithms, proximity alone supplied the reward structure needed for effective offline reinforcement learning. The study also provides a lightweight theory for when this simple approximation is sufficient."
publishedAt: "2026-08-10T15:13:40.453Z"
score: 0.85
topics:
  - "Imitation Learning"
  - "Reward Assignment"
  - "Offline Reinforcement Learning"
topicIds:
  - "imitation-learning-5ocfaj"
  - "reward-assignment-vs6azf"
  - "offline-reinforcement-learning-bnih6x"
sourceUrls:
  - "https://arxiv.org/abs/2506.06793"
---

Reward assignment typically infers rewards from expert demonstrations rather than using hand-crafted reward functions. The study asks which minimal reward structure is actually needed for offline reinforcement learning and covers 32 benchmarks across offline and online settings, alongside a lightweight theory characterizing when simple proximity approximation suffices.

With three downstream RL algorithms, proximity alone captured the reward structure necessary for effective offline reinforcement learning. Lightweight temporal correspondence produced consistent gains that were modest in the offline setting but became essential online or when multiple demonstrations were present.

The lightweight theory characterizes conditions under which simple proximity approximation suffices for reward assignment, making it a sufficiency result rather than a claim that proximity is optimal or required in all settings. The source records no additional uncertainties.
