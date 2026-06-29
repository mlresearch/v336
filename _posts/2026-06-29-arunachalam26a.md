---
title: Learning depth-3 circuits via quantum agnostic boosting
section: Original Papers
abstract: 'We initiate the study of quantum agnostic learning of phase states with
  respect to a function class $C \subseteq {c:{0,1}^n\rightarrow {0,1}}$: given copies
  of an unknown $n$-qubit state $|\psi⟩$ which has fidelity $\textsf{opt}$ with a
  phase state $|\phi_c⟩=\frac{1}{\sqrt{2^n}}\sum_{x\in {0,1}^n}(-1)^{c(x)}|x⟩$  for
  some $c\in C$, output  $|\phi⟩$ which has fidelity $|⟨\phi | \psi ⟩|^2 \geq \textsf{opt}-\varepsilon$.
  To this end, we give agnostic learning protocols for the following classes: 1. Size-$t$
  decision trees which runs in time $\textsf{poly}(n,t,1/\varepsilon)$. This also
  implies $k$-juntas can be agnostically learned in time $\textsf{poly}(n,2^k,1/\varepsilon)$.
  2. $s$-term DNF formulas in time  $\textsf{poly}(n,(s/\varepsilon)^{\log \log (s/\varepsilon)
  \cdot \log(1/\varepsilon)})$. Our main technical contribution is a quantum agnostic
  boosting protocol which converts a “weak” agnostic learner, which outputs a parity
  state $|\phi⟩$ such that $|⟨\phi|\psi⟩|^2\geq \textsf{opt}/\textsf{poly}(n)$, into
  a “strong” learner which outputs a superposition of parity states $|\phi’⟩$ such
  that $|⟨\phi’|\psi⟩|^2\geq \textsf{opt} - \varepsilon$. Using quantum agnostic boosting,
  we give a $n^{O(\log(n/\varepsilon)\cdot \log \log n)}$-time algorithm for  $\varepsilon$-learning
  $\textsf{poly}(n)$-sized depth-$3$ circuits (consisting of $\textsf{AND}$, $\textsf{OR}$,
  $\textsf{NOT}$ gates) in the uniform $\textsf{PAC}$ model given quantum examples.
  Classically, obtaining an algorithm with a similar complexity has been an open question
  in the $\textsf{PAC}$ model and our work answers this given quantum examples. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: arunachalam26a
month: 0
tex_title: Learning depth-3 circuits via quantum agnostic boosting
firstpage: 371
lastpage: 426
page: 371-426
order: 371
cycles: false
bibtex_author: Arunachalam, Srinivasan and Dutt, Arkopal and Gheorghiu, Alexandru
  and De Oliveira, Michael
author:
- given: Srinivasan
  family: Arunachalam
- given: Arkopal
  family: Dutt
- given: Alexandru
  family: Gheorghiu
- given: Michael
  family: De Oliveira
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
pdf: https://raw.githubusercontent.com/mlresearch/v336/main/assets/arunachalam26a/arunachalam26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
