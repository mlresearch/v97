---
title: 'Beyond Backprop: Online Alternating Minimization with Auxiliary Variables'
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/choromanska19a/choromanska19a.pdf
url: http://proceedings.mlr.press/v97/choromanska19a.html
abstract: Despite significant recent advances in deep neural networks, training them
  remains a challenge due to the highly non-convex nature of the objective function.
  State-of-the-art methods rely on error backpropagation, which suffers from several
  well-known issues, such as vanishing and exploding gradients, inability to handle
  non-differentiable nonlinearities and to parallelize weight-updates across layers,
  and biological implausibility. These limitations continue to motivate exploration
  of alternative training algorithms, including several recently proposed auxiliary-variable
  methods which break the complex nested objective function into local subproblems.
  However, those techniques are mainly offline (batch), which limits their applicability
  to extremely large datasets, as well as to online, continual or reinforcement learning.
  The main contribution of our work is a novel online (stochastic/mini-batch) alternating
  minimization (AM) approach for training deep neural networks, together with the
  first theoretical convergence guarantees for AM in stochastic settings and promising
  empirical results on a variety of architectures and datasets.
layout: inproceedings
id: choromanska19a
tex_title: 'Beyond Backprop: Online Alternating Minimization with Auxiliary Variables'
firstpage: 1193
lastpage: 1202
page: 1193-1202
order: 1193
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Choromanska, Anna and Cowen, Benjamin and Kumaravel, Sadhana and Luss,
  Ronny and Rigotti, Mattia and Rish, Irina and Diachille, Paolo and Gurev, Viatcheslav
  and Kingsbury, Brian and Tejwani, Ravi and Bouneffouf, Djallel
author:
- given: Anna
  family: Choromanska
- given: Benjamin
  family: Cowen
- given: Sadhana
  family: Kumaravel
- given: Ronny
  family: Luss
- given: Mattia
  family: Rigotti
- given: Irina
  family: Rish
- given: Paolo
  family: Diachille
- given: Viatcheslav
  family: Gurev
- given: Brian
  family: Kingsbury
- given: Ravi
  family: Tejwani
- given: Djallel
  family: Bouneffouf
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
  link: http://proceedings.mlr.press/v97/choromanska19a/choromanska19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
