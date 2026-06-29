---
title: Estimating Ising Models in Total Variation Distance
section: Original Papers
abstract: We consider the problem of estimating Ising models over n variables in Total
  Variation (TV) distance, given l independent samples from the model. While the statistical
  complexity of the problem is well-understood Devroye et al. (2020), identifying
  computationally and statistically efficient algorithms has been challenging. In
  particular, remarkable progress has occurred in several settings, such as when the
  underlying graph is a tree Daskalakis and Pan (2021); Bhattacharyya et al. (2021),
  when the entries of the interaction matrix follow a Gaussian distribution Gaitonde
  and Mossel (2024); Chandrasekaran and Klivans (2024), or when the bulk of its eigenvalues
  lie in a small interval Anari et al. (2024a); Koehler et al. (2024), but no unified
  framework for polynomial-time estimation in TV exists so far. Our main contribution
  is a unified analysis of the Maximum Pseudo-Likelihood Estimator (MPLE) for two
  general classes of Ising models. The first class includes models whose interaction
  matrix has a bounded operator norm. In particular, we focus on the subclass of models
  that satisfy the Modified Log-Sobolev Inequality (MLSI), a functional inequality
  that was introduced to study the convergence of the associated Glauber dynamics
  to stationarity. In the second class of models, the interaction matrix has bounded
  infinity norm (or bounded width), which is the most common assumption in the literature
  for structure learning of Ising models. We show how our general results for these
  classes yield polynomial-time algorithms and optimal or near-optimal sample complexity
  guarantees in a variety of settings. Our proofs employ a variety of tools from tensorization
  inequalities to measure decompositions and concentration bounds
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: daskalakis26a
month: 0
tex_title: Estimating Ising Models in Total Variation Distance
firstpage: 1647
lastpage: 1714
page: 1647-1714
order: 1647
cycles: false
bibtex_author: Daskalakis, Constantinos and Kandiros, Vardis and Yao, Rui
author:
- given: Constantinos
  family: Daskalakis
- given: Vardis
  family: Kandiros
- given: Rui
  family: Yao
date: 2026-06-29
address:
container-title: Proceedings of Thirty Ninth Conference on Learning Theory
volume: '336'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 6
  - 29
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/daskalakis26a/daskalakis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
