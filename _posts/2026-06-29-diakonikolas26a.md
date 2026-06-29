---
title: High-Dimensional Gaussian Mean Estimation under Realizable Contamination
section: Original Papers
abstract: We study mean estimation for a Gaussian distribution with identity covariance
  in $\mathbb{R}^d$ under a missing data scheme termed realizable $\epsilon$-contamination.
  In this model, an adversary chooses a function $r(x)$ taking values in $[0,\epsilon]$,
  and each sample $x$ is removed independently with probability $r(x)$. Recent work
  introduced this model as an intermediate-strength setting between Missing Completely
  At Random (MCAR), where missingness is independent of the data, and Missing Not
  At Random (MNAR), where missingness may depend arbitrarily on the sample values
  and can lead to non-identifiability. Prior work established information-theoretic
  upper and lower bounds for mean estimation in the realizable contamination model,
  but the proposed estimators require runtime exponential in the dimension, leaving
  open the possibility of computationally efficient algorithms in high dimensions.
  In this work, we establish an information–computation gap in the Statistical Query
  model and, as a consequence, for low-degree polynomial and polynomial-threshold-function
  algorithms. Specifically, we show that any such algorithm must either use substantially
  more samples than information-theoretically necessary or incur exponential runtime.
  We complement our lower bound with an algorithm whose sample–time tradeoff nearly
  matches our lower bound. Together, these results provide a qualitative characterization
  of the computational complexity of Gaussian mean estimation under realizable $\epsilon$-contamination.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas26a
month: 0
tex_title: High-Dimensional Gaussian Mean Estimation under Realizable Contamination
firstpage: 1814
lastpage: 1856
page: 1814-1856
order: 1814
cycles: false
bibtex_author: Diakonikolas, Ilias and Kane, Daniel M. and Pittas, Thanasis
author:
- given: Ilias
  family: Diakonikolas
- given: Daniel M.
  family: Kane
- given: Thanasis
  family: Pittas
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/diakonikolas26a/diakonikolas26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
