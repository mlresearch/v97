---
title: 'Trading Redundancy for Communication: Speeding up Distributed SGD for Non-convex
  Optimization'
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/haddadpour19a/haddadpour19a.pdf
url: http://proceedings.mlr.press/v97/haddadpour19a.html
abstract: Communication overhead is one of the key challenges that hinders the scalability
  of distributed optimization algorithms to train large neural networks. In recent
  years, there has been a great deal of research to alleviate communication cost by
  compressing the gradient vector or using local updates and periodic model averaging.
  In this paper, we advocate the use of redundancy towards communication-efficient
  distributed stochastic algorithms for non-convex optimization. In particular, we,
  both theoretically and practically, show that by properly infusing redundancy to
  the training data with model averaging, it is possible to significantly reduce the
  number of communication rounds. To be more precise, we show that redundancy reduces
  residual error in local averaging, thereby reaching the same level of accuracy with
  fewer rounds of communication as compared with previous algorithms. Empirical studies
  on CIFAR10, CIFAR100 and ImageNet datasets in a distributed environment complement
  our theoretical results; they show that our algorithms have additional beneficial
  aspects including tolerance to failures, as well as greater gradient diversity.
layout: inproceedings
id: haddadpour19a
tex_title: 'Trading Redundancy for Communication: Speeding up Distributed {SGD} for
  Non-convex Optimization'
firstpage: 2545
lastpage: 2554
page: 2545-2554
order: 2545
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Haddadpour, Farzin and Kamani, Mohammad Mahdi and Mahdavi, Mehrdad
  and Cadambe, Viveck
author:
- given: Farzin
  family: Haddadpour
- given: Mohammad Mahdi
  family: Kamani
- given: Mehrdad
  family: Mahdavi
- given: Viveck
  family: Cadambe
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
  link: http://proceedings.mlr.press/v97/haddadpour19a/haddadpour19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
