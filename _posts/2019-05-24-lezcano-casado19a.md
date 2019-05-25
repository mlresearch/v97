---
title: 'Cheap Orthogonal Constraints in Neural Networks: A Simple Parametrization
  of the Orthogonal and Unitary Group'
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/lezcano-casado19a/lezcano-casado19a.pdf
url: http://proceedings.mlr.press/v97/lezcanocasado19a.html
abstract: We introduce a novel approach to perform first-order optimization with orthogonal
  and unitary constraints. This approach is based on a parametrization stemming from
  Lie group theory through the exponential map. The parametrization transforms the
  constrained optimization problem into an unconstrained one over a Euclidean space,
  for which common first-order optimization methods can be used. The theoretical results
  presented are general enough to cover the special orthogonal group, the unitary
  group and, in general, any connected compact Lie group. We discuss how this and
  other parametrizations can be computed efficiently through an implementation trick,
  making numerically complex parametrizations usable at a negligible runtime cost
  in neural networks. In particular, we apply our results to RNNs with orthogonal
  recurrent weights, yielding a new architecture called expRNN. We demonstrate how
  our method constitutes a more robust approach to optimization with orthogonal constraints,
  showing faster, accurate, and more stable convergence in several tasks designed
  to test RNNs.
layout: inproceedings
id: lezcano-casado19a
tex_title: 'Cheap Orthogonal Constraints in Neural Networks: A Simple Parametrization
  of the Orthogonal and Unitary Group'
firstpage: 3794
lastpage: 3803
page: 3794-3803
order: 3794
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Lezcano-Casado, Mario and Mart\'{\i}nez-Rubio, David
author:
- given: Mario
  family: Lezcano-Casado
- given: David
  family: Martı́nez-Rubio
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
  link: http://proceedings.mlr.press/v97/lezcano-casado19a/lezcano-casado19a-supp.pdf
- label: Code
  link: https://github.com/Lezcano/expRNN
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
