---
title: On The Complexity of Best-Arm Identification in Non-Stationary Linear Bandits
section: Original Papers
abstract: We study the fixed-budget best-arm identification (BAI) problem in non-stationary
  linear bandits.  Concretely, given a fixed time budget $T\in \mathbb{N}$, finite
  arm set $\mathcal{X} \subset \mathbb{R}^d$, and a potentially adversarial sequence
  of unknown parameters $\lbrace \theta_t\rbrace_{t=1}^{T}$ (hence non-stationary),
  a learner aims to identify the arm with the largest cumulative reward $x_* = \arg\max_{x
  \in \mathcal{X}} x^\top\sum_{t=1}^T \theta_t$ with high probability. In this setting,
  it is well-known that i.i.d. sampling arms from the G-optimal design yields a minimax-optimal
  error probability of $\exp\left(-\Theta\left(T /  H_{G}\right)\right)$, where $H_{G}$
  scales proportionally with the dimension $d$. However, this notion of complexity
  is overly pessimistic, as it is derived from a lower bound in which the arm set
  consists only of the standard basis vectors, thus masking any potential advantages
  arising from arm sets with richer geometric structure. To address this, we establish
  an \textit{arm-set-dependent} lower bound that, in contrast, holds for any arm set.
  Motivated by the ideas underlying our lower bound, we propose the \textit{Adjacent-optimal
  design}, a specialization of the well-known $\mathcal{XY}$-optimal design, and develop
  the \textsf{Adjacent-BAI} algorithm. We prove that the error probability of \textsf{Adjacent-BAI}
  matches our lower bound up to constants, verifying the tightness of our lower bound,
  and establishing the arm-set-dependent complexity of this setting.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: maynard-zhang26a
month: 0
tex_title: On The Complexity of Best-Arm Identification in Non-Stationary Linear Bandits
firstpage: 5021
lastpage: 5052
page: 5021-5052
order: 5021
cycles: false
bibtex_author: Maynard-Zhang, Leo and Xiong, Zhihan and Jamieson, Kevin and Fazel,
  Maryam
author:
- given: Leo
  family: Maynard-Zhang
- given: Zhihan
  family: Xiong
- given: Kevin
  family: Jamieson
- given: Maryam
  family: Fazel
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/maynard-zhang26a/maynard-zhang26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
