---
title: Screening rules for Lasso with non-convex Sparse Regularizers
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/rakotomamonjy19a/rakotomamonjy19a.pdf
url: http://proceedings.mlr.press/v97/rakotomamonjy19a.html
abstract: "Leveraging on the convexity of the Lasso problem, screening rules help
  in accelerating solvers by discarding irrelevant variables, during the optimization
  process. However, because they provide better theoretical guarantees in identifying
  relevant\tvariables, several non-convex regularizers for the Lasso have been proposed
  in the literature. This work is the first that introduces a screening rule strategy
  into a non-convex Lasso solver. The approach we propose is based on a iterative
  majorization-minimization (MM) strategy that includes a screening rule in the inner
  solver and a condition for propagating screened variables between iterations of
  MM. In addition to improve efficiency of solvers, we also provide guarantees that
  the inner solver is able to identify the zeros components of its critical point
  in finite time. Our experimental analysis illustrates the significant computational
  gain brought by the new screening rule compared to classical coordinate-descent
  or proximal gradient descent methods."
layout: inproceedings
id: rakotomamonjy19a
tex_title: Screening rules for Lasso with non-convex Sparse Regularizers
firstpage: 5341
lastpage: 5350
page: 5341-5350
order: 5341
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Rakotomamonjy, Alain and Gasso, Gilles and Salmon, Joseph
author:
- given: Alain
  family: Rakotomamonjy
- given: Gilles
  family: Gasso
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
  link: http://proceedings.mlr.press/v97/rakotomamonjy19a/rakotomamonjy19a-supp.pdf
- label: Code
  link: https://github.com/arakotom/screening_ncvx_penalty
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
