---
title: Fast Score-Based Sampling via Log-Concave Reductions
section: Original Papers
abstract: 'Sampling based on score diffusions has led to striking empirical results,
  and has attracted considerable attention from various research communities.  It
  depends on the availability of (approximate) Stein score functions for various levels
  of additive noise.  We show how, in some generality, the availability of scores
  allows the general problem to be “reduced” to sampling from an adaptively constructed
  sequence of $K$ strongly log-concave (SLC) sub-problems.  The reduction is simple,
  constructive and algorithm-independent, so that any SLC sampler can be used as a
  subroutine.  Various bounds on score-based sampling complexity follow directly:
  for instance, high-accuracy SLC samplers yield $\tilde{O}(\sqrt{d} \operatorname{polylog}(1/\varepsilon))$
  guarantees for accuracy $\varepsilon$ in dimension $d$, whereas randomized midpoint
  SLC schemes yield $\tilde{O}( d^{1/3} \operatorname{poly}(1/\varepsilon))$ guarantees.  When
  the original distribution itself is SLC, we prove that $K \leq 1 + \log_2(\kappa)$,
  thereby obtaining the first efficient procedure with logarithmic dependence on the
  condition number $\kappa$; for general distributions, the quantity $K$ depends on
  the geometry of the score Hessian across the trajectory.  Our analysis is direct
  and simple, involving techniques and insights complementary to those in standard
  analyses of discretized diffusions.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wainwright26a
month: 0
tex_title: Fast Score-Based Sampling via Log-Concave Reductions
firstpage: 6592
lastpage: 6621
page: 6592-6621
order: 6592
cycles: false
bibtex_author: Wainwright, Martin J.
author:
- given: Martin J.
  family: Wainwright
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/wainwright26a/wainwright26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
