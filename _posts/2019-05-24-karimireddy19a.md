---
title: Error Feedback Fixes SignSGD and other Gradient Compression Schemes
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/karimireddy19a/karimireddy19a.pdf
url: http://proceedings.mlr.press/v97/karimireddy19a.html
abstract: Sign-based algorithms (e.g. signSGD) have been proposed as a biased gradient
  compression technique to alleviate the communication bottleneck in training large
  neural networks across multiple workers. We show simple convex counter-examples
  where signSGD does not converge to the optimum. Further, even when it does converge,
  signSGD may generalize poorly when compared with SGD. These issues arise because
  of the biased nature of the sign compression operator. We then show that using error-feedback,
  i.e. incorporating the error made by the compression operator into the next step,
  overcomes these issues. We prove that our algorithm (EF-SGD) with arbitrary compression
  operator achieves the same rate of convergence as SGD without any additional assumptions.
  Thus EF-SGD achieves gradient compression for free. Our experiments thoroughly substantiate
  the theory.
layout: inproceedings
id: karimireddy19a
tex_title: Error Feedback Fixes {S}ign{SGD} and other Gradient Compression Schemes
firstpage: 3252
lastpage: 3261
page: 3252-3261
order: 3252
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Karimireddy, Sai Praneeth and Rebjock, Quentin and Stich, Sebastian
  and Jaggi, Martin
author:
- given: Sai Praneeth
  family: Karimireddy
- given: Quentin
  family: Rebjock
- given: Sebastian
  family: Stich
- given: Martin
  family: Jaggi
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
  link: http://proceedings.mlr.press/v97/karimireddy19a/karimireddy19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
