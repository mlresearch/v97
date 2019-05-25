---
title: 'Sever: A Robust Meta-Algorithm for Stochastic Optimization'
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/diakonikolas19a/diakonikolas19a.pdf
url: http://proceedings.mlr.press/v97/diakonikolas19a.html
abstract: In high dimensions, most machine learning methods are brittle to even a
  small fraction of structured outliers. To address this, we introduce a new meta-algorithm
  that can take in a base learner such as least squares or stochastic gradient descent,
  and harden the learner to be resistant to outliers. Our method, Sever, possesses
  strong theoretical guarantees yet is also highly scalable – beyond running the base
  learner itself, it only requires computing the top singular vector of a certain
  n{\texttimes}d matrix. We apply Sever on a drug design dataset and a spam classification
  dataset, and find that in both cases it has substantially greater robustness than
  several baselines. On the spam dataset, with 1% corruptions, we achieved 7.4% test
  error, compared to 13.4%-20.5% for the baselines, and 3% error on the uncorrupted
  dataset. Similarly, on the drug design dataset, with 10% corruptions, we achieved
  1.42 mean-squared error test error, compared to 1.51-2.33 for the baselines, and
  1.23 error on the uncorrupted dataset.
layout: inproceedings
id: diakonikolas19a
tex_title: 'Sever: A Robust Meta-Algorithm for Stochastic Optimization'
firstpage: 1596
lastpage: 1606
page: 1596-1606
order: 1596
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Diakonikolas, Ilias and Kamath, Gautam and Kane, Daniel and Li, Jerry
  and Steinhardt, Jacob and Stewart, Alistair
author:
- given: Ilias
  family: Diakonikolas
- given: Gautam
  family: Kamath
- given: Daniel
  family: Kane
- given: Jerry
  family: Li
- given: Jacob
  family: Steinhardt
- given: Alistair
  family: Stewart
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
  link: http://proceedings.mlr.press/v97/diakonikolas19a/diakonikolas19a-supp.pdf
- label: Code
  link: https://github.com/hoonose/sever
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
