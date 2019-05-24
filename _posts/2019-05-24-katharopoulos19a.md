---
title: Processing Megapixel Images with Deep Attention-Sampling Models
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/katharopoulos19a/katharopoulos19a.pdf
url: http://proceedings.mlr.press/v97/katharopoulos19a.html
abstract: Existing deep architectures cannot operate on very large signals such as
  megapixel images due to computational and memory constraints. To tackle this limitation,
  we propose a fully differentiable end-to-end trainable model that samples and processes
  only a fraction of the full resolution input image. The locations to process are
  sampled from an attention distribution computed from a low resolution view of the
  input. We refer to our method as attention sampling and it can process images of
  several megapixels with a standard single GPU setup. We show that sampling from
  the attention distribution results in an unbiased estimator of the full model with
  minimal variance, and we derive an unbiased estimator of the gradient that we use
  to train our model end-to-end with a normal SGD procedure. This new method is evaluated
  on three classification tasks, where we show that it allows to reduce computation
  and memory footprint by an order of magnitude for the same accuracy as classical
  architectures. We also show the consistency of the sampling that indeed focuses
  on informative parts of the input images.
layout: inproceedings
id: katharopoulos19a
tex_title: Processing Megapixel Images with Deep Attention-Sampling Models
firstpage: 3282
lastpage: 3291
page: 3282-3291
order: 3282
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Katharopoulos, Angelos and Fleuret, Francois
author:
- given: Angelos
  family: Katharopoulos
- given: Francois
  family: Fleuret
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
  link: http://proceedings.mlr.press/v97/katharopoulos19a/katharopoulos19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
