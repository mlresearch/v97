---
title: Optimal Mini-Batch and Step Sizes for SAGA
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/gazagnadou19a/gazagnadou19a.pdf
url: http://proceedings.mlr.press/v97/gazagnadou19a.html
abstract: 'Recently it has been shown that the step sizes of a family of variance
  reduced gradient methods called the JacSketch methods depend on the expected smoothness
  constant. In particular, if this expected smoothness constant could be calculated
  a priori, then one could safely set much larger step sizes which would result in
  a much faster convergence rate. We fill in this gap, and provide simple closed form
  expressions for the expected smoothness constant and careful numerical experiments
  verifying these bounds. Using these bounds, and since the SAGA algorithm is part
  of this JacSketch family, we suggest a new standard practice for setting the step
  and mini-batch sizes for SAGA that are competitive with a numerical grid search.
  Furthermore, we can now show that the total complexity of the SAGA algorithm decreases
  linearly in the mini-batch size up to a pre-defined value: the optimal mini-batch
  size. This is a rare result in the stochastic variance reduced literature, only
  previously shown for the Katyusha algorithm. Finally we conjecture that this is
  the case for many other stochastic variance reduced methods and that our bounds
  and analysis of the expected smoothness constant is key to extending these results.'
layout: inproceedings
id: gazagnadou19a
tex_title: Optimal Mini-Batch and Step Sizes for {SAGA}
firstpage: 2142
lastpage: 2150
page: 2142-2150
order: 2142
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Gazagnadou, Nidham and Gower, Robert and Salmon, Joseph
author:
- given: Nidham
  family: Gazagnadou
- given: Robert
  family: Gower
- given: Joseph
  family: Salmon
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
  link: http://proceedings.mlr.press/v97/gazagnadou19a/gazagnadou19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
