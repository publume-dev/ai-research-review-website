---
decisionKey: "144f13b8061146688211f43e9b86d4f9e114168fced791b4fbffa3d387d68fce"
language: "en"
title: "Plan scaffolding for programming agents: explicit plans help, misaligned plans hurt"
summary: "A new systematic analysis reports that explicit plans improve programming-agent issue resolution and periodic plan reminders reduce violations, while subpar plans can perform worse than no plan. The evidence is specific to SWE-agent on SWE-bench Verified and Pro, so other agents are not covered."
publishedAt: "2026-08-10T15:13:40.453Z"
score: 0.9
topics:
  - "AI Agent Plan Compliance"
topicIds:
  - "ai-agent-plan-compliance-184695s"
sourceUrls:
  - "https://arxiv.org/abs/2604.12147"
---

The study analyzes plan compliance in programming agents. It uses the SWE-agent with four different large language models on the SWE-bench Verified and Pro benchmarks, under eight plan variations, collecting 21,120 trajectories for a systematic comparison of how plan format affects agent behavior.

According to the study, when agents receive no explicit plan they fall back on internalized workflows that are often incomplete, overfit, or inconsistently applied. Providing the standard plan raises issue resolution, and periodic plan reminders reduce plan violations and improve task success. A lower-quality plan hurts performance more than having no plan, and adding extra task-relevant phases early can degrade performance when those phases do not align with the model's internal problem-solving strategy.

The findings come from one agent and two benchmark suites; generalization to other programming agents and to real-world programming tasks is not established. The observed relationships are specific to SWE-agent on SWE-bench Verified and Pro.
