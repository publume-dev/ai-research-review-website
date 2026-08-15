---
decisionKey: "ab0c180d2e0139244cd5f5b7b96c52e4b408017ddb272366cec6867a6f94ef11"
language: "en"
title: "Federated Parameter-Efficient Framework for Privacy-Preserving Multi-Institutional Medical LLM Adaptation"
summary: "The new Fed-MedLoRA framework transmits only low-rank adapters instead of full model weights and introduces adaptive aggregation to address cross-site heterogeneity, consistently improving performance on clinical information extraction across five independent patient cohorts."
publishedAt: "2026-08-15T03:03:56.055Z"
score: 0.85
topics:
  - "Federated Learning"
  - "Medical AI"
  - "Large Language Models"
topicIds:
  - "federated-learning-tztnd3"
  - "medical-ai-112vis2"
  - "large-language-models-1okubv8"
sourceUrls:
  - "https://arxiv.org/abs/2601.22124"
---

The study addresses the challenge of adapting large language models (LLMs) in medicine across multiple institutions by proposing a parameter-efficient federated learning framework, Fed-MedLoRA, and its enhanced version Fed-MedLoRA+. The core design transmits only low-rank adapters rather than full model weights, with Fed-MedLoRA+ incorporating adaptive aggregation to handle cross-site data heterogeneity.

Evaluated on clinical information extraction across five independent patient cohorts totaling 42,198 entities and 41,570 relations, the framework consistently improved extraction performance and generalization compared to zero-shot, fine-tuned LLMs, domain-specific BERT models, and federated baselines. In a real-world case study using clinical notes from the Yale New Haven Health System, the framework demonstrated strong performance under low-resource new-site deployment.

The paper is a preprint (arXiv version 3), and although 'just accepted' may imply peer review, it is not explicitly stated. Specific effect sizes and benchmark deltas are not provided in the abstract.
