---
title: A Tree-Based Method for Fast Repeated Sampling of Determinantal Point Processes
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/gillenwater19a/gillenwater19a.pdf
url: http://proceedings.mlr.press/v97/gillenwater19a.html
abstract: 'It is often desirable in recommender systems and other information retrieval
  applications to provide diverse results, and determinantal point processes (DPPs)
  have become a popular way to capture the trade-off between the quality of individual
  results and the diversity of the overall set. However, sampling from a DPP is inherently
  expensive: if the underlying collection contains N items, then generating each DPP
  sample requires time linear in N following a one-time preprocessing phase. Additionally,
  results often need to be personalized to a user, but standard approaches to personalization
  invalidate the preprocessing, making personalized samples especially expensive.
  In this work we address both of these shortcomings. First, we propose a new algorithm
  for generating DPP samples in time logarithmic in N, following a slightly more expensive
  preprocessing phase. We then extend the algorithm to support arbitrary query-time
  feature weights, allowing us to generate samples customized to individual users
  while still retaining logarithmic runtime; experiments show our approach runs over
  300 times faster than traditional DPP sampling on collections of 100,000 items for
  samples of size 10.'
layout: inproceedings
id: gillenwater19a
tex_title: A Tree-Based Method for Fast Repeated Sampling of Determinantal Point Processes
firstpage: 2260
lastpage: 2268
page: 2260-2268
order: 2260
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Gillenwater, Jennifer and Kulesza, Alex and Mariet, Zelda and Vassilvtiskii,
  Sergei
author:
- given: Jennifer
  family: Gillenwater
- given: Alex
  family: Kulesza
- given: Zelda
  family: Mariet
- given: Sergei
  family: Vassilvtiskii
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
  link: http://proceedings.mlr.press/v97/gillenwater19a/gillenwater19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
