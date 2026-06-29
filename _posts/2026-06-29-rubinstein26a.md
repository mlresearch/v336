---
title: Private Linear Regression via a Down-Sensitivity to Privacy Reduction
section: Original Papers
abstract: We present a sample- and time-efficient $(\varepsilon,\delta)$-differentially
  private (DP) algorithm for $d$-dimensional linear regression with a sample complexity
  of \[ n_{\mathrm{STAR}} = \widetilde{O}\left(\frac{d}{\alpha^2} + \frac{d \log(1/\delta)}{\alpha
  \varepsilon} + \frac{d \log(1/\delta)}{\varepsilon}\right) + o(d). \]{This} improves
  upon prior polynomial-time algorithms whose sample complexity either depends on
  the condition number of the design matrix $\kappa$ (for DP-SGD with gradient clipping),
  scales quadratically with the dimension (for Sum-of-Squares algorithms) or with
  the inverse of the privacy parameter (for outlier removal algorithms such as insufficient
  statistics perturbation or ISSP), \[ n_{\mathrm{SoS}} = \widetilde{\Omega}\left(\frac{d^2}{\alpha^2}\right),
  \quad n_{\mathrm{DP\mbox{-}SGD}} = \widetilde{\Omega}\left(\frac{d \sqrt{\kappa}}{\varepsilon}\right),
  \quad n_{\mathrm{ISSP}} = \widetilde{\Omega}\left(\frac{d}{\varepsilon^2}\right).
  \]{Our} algorithm is based on a novel \emph{subsample-test-aggregate} (STA) approach
  for ensuring privacy given only bounded \emph{down-sensitivity} – robustness to
  removal, but not addition, of a small number of samples. The intuition that down-sensitivity
  should be related to privacy is not new, but STA formalizes this by providing an
  \emph{efficient black-box reduction from down-sensitivity to privacy} which we expect
  to be applicable beyond the setting of linear regression.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rubinstein26a
month: 0
tex_title: Private Linear Regression via a Down-Sensitivity to Privacy Reduction
firstpage: 5662
lastpage: 5720
page: 5662-5720
order: 5662
cycles: false
bibtex_author: Rubinstein, Ittai and Ge, Chris and Hopkins, Samuel B.
author:
- given: Ittai
  family: Rubinstein
- given: Chris
  family: Ge
- given: Samuel B.
  family: Hopkins
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/rubinstein26a/rubinstein26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
