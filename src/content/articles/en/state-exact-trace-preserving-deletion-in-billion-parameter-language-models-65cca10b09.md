---
decisionKey: "65cca10b0958e571f2a1fa5ebe599612f63b0df911cdc34464ebe8e80ee1f99e"
language: "en"
title: "State-Exact Trace-Preserving Deletion in Billion-Parameter Language Models"
summary: "A new method achieves state-exact sample deletion in billion-parameter language models by replaying from a token store that excludes requested rows. This result sets a new precision benchmark for machine unlearning."
publishedAt: "2026-08-16T03:16:05.622Z"
score: 0.95
topics:
  - "Machine Unlearning"
  - "Language Models"
  - "Model Deletion"
topicIds:
  - "machine-unlearning-pjo9s7"
  - "language-models-5wxasf"
  - "model-deletion-u39lns"
sourceUrls:
  - "https://arxiv.org/abs/2508.12220"
---

Machine unlearning in language models aims to remove specific information from training data. This paper proposes a method for state-exact deletion, meaning the final model and optimizer states should match a training run that never saw the deleted data. The method relies on recording execution provenance and replaying from a token store that excludes requested rows. The paper is an arXiv preprint and has not been peer-reviewed.

Replaying from a token store excluding requested rows reproduces a separately executed trace oracle bit-for-bit in model and optimizer state in pinned single-GPU environments. Pythia 160M is exact across four deletion geometries; Pythia 2.8B matches all 2,775,208,960 model-state elements for a random 5% request; Llama 3.2 1B is exact after omitting 400 of 4,000 TOFU examples from replay storage. These results demonstrate state exactness at billion-parameter scale.

The guarantee is prospective: the original run must record execution provenance and retain an eligible uncontaminated checkpoint. State exactness does not establish cheap deletion, because dispersed requests can force nearly full replay. The paper's standardized TOFU/OpenUnlearning measurements are descriptive diagnostics only, lacking matched controls for a causal behavioral claim.
