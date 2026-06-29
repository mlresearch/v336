---
title: Swap Regret Minimization Through Response-Based Approachability
section: Original Papers
abstract: 'We consider the problem of minimizing different notions of swap regret
  in online optimization. These forms of regret are tightly connected to correlated
  equilibrium concepts in games, and have been more recently shown to guarantee non-manipulability
  against strategic adversaries. The only computationally efficient algorithm for
  minimizing linear swap regret over a general convex set in $\mathbb{R}^d$ was developed
  recently by Daskalakis, Farina, Fishelson, Pipis, and Schneider (STOC ’25). However,
  it incurs a highly suboptimal regret bound of $\Omega(d^4 \sqrt{T})$ and also relies
  on computationally intensive calls to the ellipsoid algorithm at each iteration.
  In this paper, we develop a significantly simpler, computationally efficient algorithm
  that guarantees $O(d \sqrt{T})$ linear swap regret for a general convex set that
  has been preconditioned via the John ellipsoid. Our algorithm leverages the powerful
  response-based approachability framework of Bernstein and Shimkin (JMLR ’15)—previously
  overlooked in the line of work on swap regret minimization—and simultaneously minimizes
  profile swap regret, which was recently shown to guarantee non-manipulability. Moreover,
  we establish a matching information-theoretic lower bound: any learner must incur
  in expectation $\Omega(d \sqrt{T})$ linear swap regret for large enough $T$, even
  when the set is centrally symmetric. This also shows that the classic algorithm
  of Gordon, Greenwald, and Marks (ICML ’08) is existentially optimal for minimizing
  linear swap regret, although it is computationally inefficient. Finally, we extend
  our approach to minimize regret with respect to the set of swap deviations with
  polynomial dimension, unifying and strengthening recent results in equilibrium computation
  and online learning.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: anagnostides26a
month: 0
tex_title: Swap Regret Minimization Through Response-Based Approachability
firstpage: 195
lastpage: 223
page: 195-223
order: 195
cycles: false
bibtex_author: Anagnostides, Ioannis and Farina, Gabriele and Fishelson, Maxwell and
  Luo, Haipeng and Schneider, Jon
author:
- given: Ioannis
  family: Anagnostides
- given: Gabriele
  family: Farina
- given: Maxwell
  family: Fishelson
- given: Haipeng
  family: Luo
- given: Jon
  family: Schneider
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/anagnostides26a/anagnostides26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
