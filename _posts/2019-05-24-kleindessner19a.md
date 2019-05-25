---
title: Fair k-Center Clustering for Data Summarization
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/kleindessner19a/kleindessner19a.pdf
url: http://proceedings.mlr.press/v97/kleindessner19a.html
abstract: In data summarization we want to choose $k$ prototypes in order to summarize
  a data set. We study a setting where the data set comprises several demographic
  groups and we are restricted to choose $k_i$ prototypes belonging to group $i$.
  A common approach to the problem without the fairness constraint is to optimize
  a centroid-based clustering objective such as $k$-center. A natural extension then
  is to incorporate the fairness constraint into the clustering problem. Existing
  algorithms for doing so run in time super-quadratic in the size of the data set,
  which is in contrast to the standard $k$-center problem being approximable in linear
  time. In this paper, we resolve this gap by providing a simple approximation algorithm
  for the $k$-center problem under the fairness constraint with running time linear
  in the size of the data set and $k$. If the number of demographic groups is small,
  the approximation guarantee of our algorithm only incurs a constant-factor overhead.
layout: inproceedings
id: kleindessner19a
tex_title: Fair k-Center Clustering for Data Summarization
firstpage: 3448
lastpage: 3457
page: 3448-3457
order: 3448
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Kleindessner, Matth{\"a}us and Awasthi, Pranjal and Morgenstern, Jamie
author:
- given: Matthäus
  family: Kleindessner
- given: Pranjal
  family: Awasthi
- given: Jamie
  family: Morgenstern
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
  link: http://proceedings.mlr.press/v97/kleindessner19a/kleindessner19a-supp.pdf
- label: Code
  link: https://github.com/matthklein/fair_k_center_clustering
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
