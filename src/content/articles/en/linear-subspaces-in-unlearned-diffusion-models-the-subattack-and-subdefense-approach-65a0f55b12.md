---
decisionKey: "65a0f55b12c9cf7fc83a85e92ba99ab6f33f3ba6d11e5e7b35dabca3010be0a9"
language: "en"
title: "Linear Subspaces in Unlearned Diffusion Models: The SubAttack and SubDefense Approach"
summary: "A new study reveals that erased concepts in unlearned diffusion models persist as linear subspaces, and introduces a stronger attack and defense method."
publishedAt: "2026-08-18T03:10:36.725Z"
score: 0.82
topics:
  - "Diffusion Models"
  - "Machine Learning Security"
topicIds:
  - "diffusion-models-1torb32"
  - "machine-learning-security-12tncy"
sourceUrls:
  - "https://arxiv.org/abs/2504.21307"
---

Diffusion models are often 'unlearned' to remove unsafe or copyrighted concepts. However, the study finds that even after a model has been trained to generate a specific concept, the concept still persists as a coherent, interpretable linear subspace in the token embedding space.

The paper proposes an attack called SubAttack, which learns a set of orthogonal attack token embeddings that are linear combinations of textual elements. These combinations reveal that unlearned models retain the target concept through related textual components. SubAttack is more powerful and transferable across text prompts, initial noises, and unlearned models than prior attacks. Correspondingly, their proposed defense, SubDefense, projects out the discovered subspace and provides stronger robustness than existing defenses while better preserving safe generation quality.

The paper is a preprint and has not been peer-reviewed; therefore, the robustness of the experimental results and the generalizability of the findings are not independently verified.
