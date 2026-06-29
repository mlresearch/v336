---
title: Online Convex Optimization with Sublinear Noisy Probes
section: Original Papers
abstract: " We study Online Convex Optimization (OCO) over a convex set $K\\subseteq
  \\mathbb R^d$, where in each round $t$ the learner selects $x_t\\in K$ and then
  observes a convex loss $f_t:K\\to[0,1]$, with the goal of minimizing regret to the
  best fixed decision in hindsight. We introduce a unified probing model that generalizes
  two recent lines of work: sublinear \\emph{best-expert} queries in the experts setting,
  and pairwise (comparison-based) feedback available every round in OCO. In our framework,
  the learner has a budget of $k\\le T$ \\emph{pairwise probes}; on a probed round
  it may query two points and learn which one has smaller loss. Our main result shows
  that even a \\emph{sublinear and noisy} probe budget can provably improve worst-case
  regret in the full feedback OCO regime. With $k$ $\\delta$-noisy pairwise probes,
  we obtain: $ {\\textup{\\textsc{Reg}}}_T \\le O\\left(\\min\\left\\{\\sqrt{dT\\ln
  T},; \\frac{dT\\ln T}{k|1-2\\delta|}\\right\\}\\right) $, which is tight (up to
  logarithmic factors in $T$) across $T$, $k$ and $\\delta$. Specifically regarding
  the noise parameter $\\delta \\in [0,1]$,  the regret guarantee smoothly degrades
  as the oracle response approaches a coin flip, i.e., $\\delta$ is close to $\\frac{1}{2}$.
  When applying the same techniques to a finite $K$ for the prediction with $d$ experts
  setting, the resulting rates are instead completely tight in all parameters, including
  $d$. Our analysis gives a streamlined treatment of pairwise probing in OCO by quantifying
  the benefit of probing via a variance reduction effect, combined with a second-order
  (variance-based) analysis of Continuous Exponential Weights."
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: di-gregorio26a
month: 0
tex_title: Online Convex Optimization with Sublinear Noisy Probes
firstpage: 1938
lastpage: 1962
page: 1938-1962
order: 1938
cycles: false
bibtex_author: "{Di Gregorio}, Simone and Gupta, Anupam and Leonardi, Stefano and
  Russo, Matteo"
author:
- given: Simone
  family: Di Gregorio
- given: Anupam
  family: Gupta
- given: Stefano
  family: Leonardi
- given: Matteo
  family: Russo
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/di-gregorio26a/di-gregorio26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
