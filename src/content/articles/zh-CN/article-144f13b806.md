---
decisionKey: "144f13b8061146688211f43e9b86d4f9e114168fced791b4fbffa3d387d68fce"
language: "zh-CN"
title: "编程智能体的计划脚手架：显式计划有益，错位计划有害"
summary: "一项新的系统分析显示，显式计划能提升编程智能体的问题解决效果，定期提醒计划可减少违规，而劣质计划的表现可能比没有计划更差。证据来自 SWE-agent 在 SWE-bench Verified 和 Pro 上的评估，尚不能涵盖其他智能体。"
publishedAt: "2026-08-10T15:13:40.453Z"
score: 0.9
topics:
  - "AI Agent Plan Compliance"
topicIds:
  - "ai-agent-plan-compliance-184695s"
sourceUrls:
  - "https://arxiv.org/abs/2604.12147"
---

该研究考察编程智能体对计划的遵循情况。分析基于 SWE-agent 在 SWE-bench Verified 和 Pro 上使用四个不同大语言模型、八种计划变体收集的 21,120 条轨迹，用于系统比较计划形式对智能体行为的影响。

研究发现，没有显式计划时，智能体会退回到内部化的工作流程，而这些流程往往不完整、过拟合或应用不一致。提供标准计划能提高问题解决率，定期提醒计划可以减少计划违规并提升任务成功率。质量不佳的计划比没有计划更损害性能；如果在早期插入与模型内部解题策略不一致的额外任务相关阶段，也可能使性能下降。

这些结论基于单一智能体和两个基准测试集，对其他编程智能体及真实编程任务的推广性尚未得到证实。观察到的关系仅限于 SWE-agent 在 SWE-bench Verified 和 Pro 上的表现。
