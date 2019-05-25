---
title: Greedy Layerwise Learning Can Scale To ImageNet
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/belilovsky19a/belilovsky19a.pdf
url: http://proceedings.mlr.press/v97/belilovsky19a.html
abstract: Shallow supervised 1-hidden layer neural networks have a number of favorable
  properties that make them easier to interpret, analyze, and optimize than their
  deep counterparts, but lack their representational power. Here we use 1-hidden layer
  learning problems to sequentially build deep networks layer by layer, which can
  inherit properties from shallow networks. Contrary to previous approaches using
  shallow networks, we focus on problems where deep learning is reported as critical
  for success. We thus study CNNs on image classification tasks using the large-scale
  ImageNet dataset and the CIFAR-10 dataset. Using a simple set of ideas for architecture
  and training we find that solving sequential 1-hidden-layer auxiliary problems lead
  to a CNN that exceeds AlexNet performance on ImageNet. Extending this training methodology
  to construct individual layers by solving 2-and-3-hidden layer auxiliary problems,
  we obtain an 11-layer network that exceeds several members of the VGG model family
  on ImageNet, and can train a VGG-11 model to the same accuracy as end-to-end learning.
  To our knowledge, this is the first competitive alternative to end-to-end training
  of CNNs that can scale to ImageNet. We illustrate several interesting properties
  of these models and conduct a range of experiments to study the properties this
  training induces on the intermediate layers.
layout: inproceedings
id: belilovsky19a
tex_title: Greedy Layerwise Learning Can Scale To {I}mage{N}et
firstpage: 583
lastpage: 593
page: 583-593
order: 583
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Belilovsky, Eugene and Eickenberg, Michael and Oyallon, Edouard
author:
- given: Eugene
  family: Belilovsky
- given: Michael
  family: Eickenberg
- given: Edouard
  family: Oyallon
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
  link: http://proceedings.mlr.press/v97/belilovsky19a/belilovsky19a-supp.pdf
- label: Code
  link: https://github.com/eugenium/layerCNN
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
