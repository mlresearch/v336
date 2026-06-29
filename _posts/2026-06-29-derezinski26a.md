---
title: The matrix-vector complexity of Ax=b
section: Original Papers
abstract: Matrix–vector algorithms, particularly Krylov subspace methods, are widely
  viewed as the most effective algorithms for solving large systems of linear equations.
  This paper establishes lower bounds on the worst-case number of matrix–vector products
  needed by such an algorithm to approximately solve a general linear system. The
  first main result is that, for any matrix–vector algorithm which is allowed the
  use of randomization and can perform products with both a matrix and its transpose,
  $\Omega(\kappa \log(1/\varepsilon))$ matrix–vector products are necessary to solve
  a linear system with condition number $\kappa$ to accuracy $\varepsilon$, matching
  an upper bound for conjugate gradient on the normal equations. The second main result
  is that one-sided algorithms, which lack access to the transpose, must use $n$ matrix–vector
  products to solve an $n \times n$ linear system, even when the problem is perfectly
  conditioned. Both main results include explicit constants that match known upper
  bounds up to a factor of four. These results rigorously demonstrate the limitations
  of matrix–vector algorithms and confirm the optimality of widely used Krylov subspace
  algorithms.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: derezinski26a
month: 0
tex_title: The matrix-vector complexity of Ax=b
firstpage: 1737
lastpage: 1770
page: 1737-1770
order: 1737
cycles: false
bibtex_author: Derezi{\'n}ski, Micha{\l} and Epperly, Ethan N and Meyer, Raphael A
author:
- given: Michał
  family: Dereziński
- given: Ethan N
  family: Epperly
- given: Raphael A
  family: Meyer
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/derezinski26a/derezinski26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
