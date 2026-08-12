---
decisionKey: "9a60031e83709fa4b0230a24db1b5af0311114283ebb10a67882ff716468d927"
language: "en"
title: "Random Reshuffling Does Not Generally Repair SignSGD's Gradient-Magnitude Bias in Nonconvex Optimization"
summary: "A new arXiv preprint proves that random reshuffling does not generally repair signSGD's bias from discarding gradient magnitudes, and supplies finite-time convergence bounds for SignRR plus a variance-reduced SignRVR variant."
publishedAt: "2026-08-12T05:46:09.130Z"
score: 0.84
topics:
  - "Nonconvex Optimization"
  - "Sign-based Gradient Methods"
  - "Stochastic Optimization"
topicIds:
  - "nonconvex-optimization-wtzjgs"
  - "sign-based-gradient-methods-151q5es"
  - "stochastic-optimization-1qc7pb1"
sourceUrls:
  - "https://arxiv.org/abs/2310.15976"
---

This arXiv preprint studies signSGD with random reshuffling (SignRR) for nonconvex finite-sum optimization. The authors' central question is whether reshuffling repairs the bias introduced by sign-based methods when they discard gradient magnitudes; the paper reports that, in general, it does not.

The analysis includes a one-dimensional two-component strongly convex quadratic example where the expected gradient norm at every SignRR inner iterate equals 1/2. The main finite-time bound is alignment-explicit: O(log(nT)/sqrt(nT)+epsilon_align), where epsilon_align measures the averaged loss of descent caused by component-sign misalignment. A horizon-tuned constant stepsize improves the vanishing term to O(1/sqrt(nT)), and a remaining-set alignment condition yields a residual-free O(1/sqrt(nT)) guarantee. The alignment term is upper bounded by twice the averaged mean absolute gradient error and, in turn, by twice an averaged coordinatewise conditional root-mean-square error. As a variance-reduced alternative, SignRVR signs an SVRG estimator anchored at the beginning of every epoch and obtains a residual-free O(sqrt(d/T)) averaged l1-stationarity bound.

The source is an arXiv preprint; the abstract does not show peer-review status, and it does not include full proofs or empirical validation. Thus the counterexample and the bounds are analytical claims from a preprint rather than peer-reviewed, experimentally verified results.
