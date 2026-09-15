---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an undergraduate student in the Honors Program in Mathematics and Applied Mathematics at Fudan University. My research focuses on optimization and learning methods for decision-making under uncertainty, with a parallel interest in geometric data analysis.

Research Interests
======

- Simulation optimization
- Stochastic optimization
- Statistical learning
- Data-driven decision making

Current Research
======

### Incremental Kernel Ridge Regression for Online Simulation Optimization

I am developing an RKHS-based incremental kernel ridge regression method for simulation optimization. The framework updates its surrogate model as new simulation observations arrive, avoiding repeated fitting from scratch and reducing computational complexity from $O(n^3)$ to $O(n^2k)$, where $k$ is the number of update iterations.

For slowly time-varying problems, the project introduces a “hard-move, soft-update” strategy that combines moving-window decision updates with incremental kernel-atom updates. This helps stabilize decisions under drift and high simulation noise.

**Advisor:** Prof. Jianqiang Hu, School of Management, Fudan University
**Since:** March 2026

### Multiscale Bias Cancellation for Accurate Manifold Estimation

I am developing a general multiscale extrapolation theory for manifold fitting. By identifying and canceling leading geometric bias, the method improves approximation error from $O(\sigma^2)$ to $O(\sigma^4)$ under regularity conditions. We validate the resulting higher-order estimators through simulations and real-data experiments on multiple manifolds.

**Advisors:** Prof. Zhigang Yao and Prof. Bingjie Li
**Affiliation:** Shanghai Institute for Mathematics and Interdisciplinary Sciences
**Since:** June 2026

Selected Project
======

### Graph-Grounded Bayesian Inference for Uncertainty-Aware LLM Evaluation

I developed a Bayesian framework that models latent response quality and judge variability for calibrated LLM evaluation. The end-to-end pipeline supports repeated multi-judge scoring, uncertainty estimation, adaptive stopping, and model-level aggregation across models, datasets, and judge configurations.

Technical Skills
======

**Programming:** Python, C++, PyTorch
**Tools:** Git, BLAS/LAPACK, LaTeX
