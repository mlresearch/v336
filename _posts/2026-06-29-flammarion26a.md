---
title: Space-Efficient Language Generation in the Limit
section: Original Papers
abstract: We initiate a resource-aware theory of \textit{language generation in the
  limit} under the minimal constraint of space efficiency. In our framework, a learner
  observes an adversarial positive stream from a target language $K$ and must eventually
  output a hallucination-free hypothesis language $L \subseteq K$ while omitting at
  most $\Delta$ strings of $K$. We focus on $\mathcal{C}_{s,k}$, the collection of
  languages recognized by DFAs with at most $s$ states over an alphabet of size $k$,
  as the natural hypothesis class for memory-bounded learners. In the exponential-space
  regime, we prove that a learner can exactly identify the target $K$. Under a stricter
  memory budget, we characterize the strongest possible generation guarantees. In
  particular, we present a streaming algorithm using $\mathrm{poly}(s,k)$ space that
  converges to a hypothesis with generation gap $\Delta = O(k^{2s-2})$. Moreover,
  the learned hypothesis captures every string in $K$ of length at least $2s-1$. We
  complement this result with a near-matching lower bound through a reduction from
  a standard communication complexity problem. Specifically, achieving generation
  gap $\Delta \le k^{(1-\varepsilon)s}$ requires $k^{\Omega(\varepsilon s)}$ memory.
  Together, these results reveal a sharp transition between polynomial-space generation
  and exponential-space exact identification.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: flammarion26a
month: 0
tex_title: Space-Efficient Language Generation in the Limit
firstpage: 2477
lastpage: 2502
page: 2477-2502
order: 2477
cycles: false
bibtex_author: Flammarion, Nicolas and Pabbaraju, Chirag and Papazov, Hristo and Stouras,
  Miltiadis and Svensson, Ola
author:
- given: Nicolas
  family: Flammarion
- given: Chirag
  family: Pabbaraju
- given: Hristo
  family: Papazov
- given: Miltiadis
  family: Stouras
- given: Ola
  family: Svensson
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/flammarion26a/flammarion26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
