---
title: 'Voronoi Boundary Classification: A High-Dimensional Geometric Approach via
  Weighted Monte Carlo Integration'
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/polianskii19a/polianskii19a.pdf
url: http://proceedings.mlr.press/v97/polianskii19a.html
abstract: Voronoi cell decompositions provide a classical avenue to classification.
  Typical approaches however only utilize point-wise cell-membership information by
  means of nearest neighbor queries and do not utilize further geometric information
  about Voronoi cells since the computation of Voronoi diagrams is prohibitively expensive
  in high dimensions. We propose a Monte-Carlo integration based approach that instead
  computes a weighted integral over the boundaries of Voronoi cells, thus incorporating
  additional information about the Voronoi cell structure. We demonstrate the scalability
  of our approach in up to 3072 dimensional spaces and analyze convergence based on
  the number of Monte Carlo samples and choice of weight functions. Experiments comparing
  our approach to Nearest Neighbors, SVM and Random Forests indicate that while our
  approach performs similarly to Random Forests for large data sizes, the algorithm
  exhibits non-trivial data-dependent performance characteristics for smaller datasets
  and can be analyzed in terms of a geometric confidence measure, thus adding to the
  repertoire of geometric approaches to classification while having the benefit of
  not requiring any model changes or retraining as new training samples or classes
  are added.
layout: inproceedings
id: polianskii19a
tex_title: 'Voronoi Boundary Classification: A High-Dimensional Geometric Approach
  via Weighted {M}onte {C}arlo Integration'
firstpage: 5162
lastpage: 5170
page: 5162-5170
order: 5162
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Polianskii, Vladislav and Pokorny, Florian T.
author:
- given: Vladislav
  family: Polianskii
- given: Florian T.
  family: Pokorny
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
  link: http://proceedings.mlr.press/v97/polianskii19a/polianskii19a-supp.pdf
- label: Code
  link: https://github.com/vlpolyansky/voronoi-boundary-classifier
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
