---
title: The Hidden Cost of Approximation in Online Mirror Descent
section: Original Papers
abstract: 'Online mirror descent (OMD) is a fundamental algorithmic paradigm that
  underlies many algorithms in optimization, machine learning and sequential decision-making.
  The OMD iterates are defined as solutions to optimization subproblems which, oftentimes,
  can be solved only approximately, leading to an \emph{inexact} version of the algorithm.
  Nonetheless, existing OMD analyses typically assume an idealized error free setting,
  thereby limiting our understanding of performance guarantees that should be expected
  in practice. In this work we initiate a systematic study into inexact OMD, and uncover
  an intricate relation between regularizer smoothness and robustness to approximation
  errors. When the regularizer is uniformly smooth, we establish a tight bound on
  the excess regret due to errors. Then, for barrier regularizers over the simplex
  and its subsets, we identify a sharp separation: negative entropy requires exponentially
  small errors to avoid linear regret, whereas log-barrier and Tsallis regularizers
  remain robust even when the errors are only polynomial. Finally, we show that when
  the losses are stochastic and the domain is the simplex, negative entropy regains
  robustness - but this property does not extend to all subsets, where exponentially
  small errors are again necessary to avoid suboptimal regret.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schlisselberg26a
month: 0
tex_title: The Hidden Cost of Approximation in Online Mirror Descent
firstpage: 5785
lastpage: 5827
page: 5785-5827
order: 5785
cycles: false
bibtex_author: Schlisselberg, Ofir and Sherman, Uri and Koren, Tomer and Mansour,
  Yishay
author:
- given: Ofir
  family: Schlisselberg
- given: Uri
  family: Sherman
- given: Tomer
  family: Koren
- given: Yishay
  family: Mansour
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/schlisselberg26a/schlisselberg26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
