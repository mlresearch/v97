---
title: 'Guided evolutionary strategies: augmenting random search with surrogate gradients'
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/maheswaranathan19a/maheswaranathan19a.pdf
url: http://proceedings.mlr.press/v97/maheswaranathan19a.html
abstract: Many applications in machine learning require optimizing a function whose
  true gradient is unknown or computationally expensive, but where surrogate gradient
  information, directions that may be correlated with the true gradient, is cheaply
  available. For example, this occurs when an approximate gradient is easier to compute
  than the full gradient (e.g. in meta-learning or unrolled optimization), or when
  a true gradient is intractable and is replaced with a surrogate (e.g. in reinforcement
  learning or training networks with discrete variables). We propose Guided Evolutionary
  Strategies (GES), a method for optimally using surrogate gradient directions to
  accelerate random search. GES defines a search distribution for evolutionary strategies
  that is elongated along a subspace spanned by the surrogate gradients and estimates
  a descent direction which can then be passed to a first-order optimizer. We analytically
  and numerically characterize the tradeoffs that result from tuning how strongly
  the search distribution is stretched along the guiding subspace and use this to
  derive a setting of the hyperparameters that works well across problems. We evaluate
  GES on several example problems, demonstrating an improvement over both standard
  evolutionary strategies and first-order methods that directly follow the surrogate
  gradient.
layout: inproceedings
id: maheswaranathan19a
tex_title: 'Guided evolutionary strategies: augmenting random search with surrogate
  gradients'
firstpage: 4264
lastpage: 4273
page: 4264-4273
order: 4264
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Maheswaranathan, Niru and Metz, Luke and Tucker, George and Choi, Dami
  and Sohl-Dickstein, Jascha
author:
- given: Niru
  family: Maheswaranathan
- given: Luke
  family: Metz
- given: George
  family: Tucker
- given: Dami
  family: Choi
- given: Jascha
  family: Sohl-Dickstein
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
  link: http://proceedings.mlr.press/v97/maheswaranathan19a/maheswaranathan19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
