---
title: Replica Conditional Sequential Monte Carlo
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/shestopaloff19a/shestopaloff19a.pdf
url: http://proceedings.mlr.press/v97/shestopaloff19a.html
abstract: We propose a Markov chain Monte Carlo (MCMC) scheme to perform state inference
  in non-linear non-Gaussian state-space models. Current state-of-the-art methods
  to address this problem rely on particle MCMC techniques and its variants, such
  as the iterated conditional Sequential Monte Carlo (cSMC) scheme, which uses a Sequential
  Monte Carlo (SMC) type proposal within MCMC. A deficiency of standard SMC proposals
  is that they only use observations up to time $t$ to propose states at time $t$
  when an entire observation sequence is available. More sophisticated SMC based on
  lookahead techniques could be used but they can be difficult to put in practice.
  We propose here replica cSMC where we build SMC proposals for one replica using
  information from the entire observation sequence by conditioning on the states of
  the other replicas. This approach is easily parallelizable and we demonstrate its
  excellent empirical performance when compared to the standard iterated cSMC scheme
  at fixed computational complexity.
layout: inproceedings
id: shestopaloff19a
tex_title: Replica Conditional Sequential {M}onte {C}arlo
firstpage: 5749
lastpage: 5757
page: 5749-5757
order: 5749
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Shestopaloff, Alex and Doucet, Arnaud
author:
- given: Alex
  family: Shestopaloff
- given: Arnaud
  family: Doucet
date: 2019-05-24
container-title: Proceedings of the 36th International Conference on Machine Learning
genre: inproceedings
issued:
  date-parts:
  - 2019
  - 5
  - 24
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v97/shestopaloff19a/shestopaloff19a-supp.pdf
- label: Code
  link: https://github.com/ayshestopaloff/replicacsmc
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
