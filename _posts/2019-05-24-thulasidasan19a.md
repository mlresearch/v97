---
title: Combating Label Noise in Deep Learning using Abstention
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/thulasidasan19a/thulasidasan19a.pdf
url: http://proceedings.mlr.press/v97/thulasidasan19a.html
abstract: We introduce a novel method to combat label noise when training deep neural
  networks for classification. We propose a loss function that permits abstention
  during training thereby allowing the DNN to abstain on confusing samples while continuing
  to learn and improve classification performance on the non-abstained samples. We
  show how such a deep abstaining classifier (DAC) can be used for robust learning
  in the presence of different types of label noise. In the case of structured or
  systematic label noise {–} where noisy training labels or confusing examples are
  correlated with underlying features of the data{–} training with abstention enables
  representation learning for features that are associated with unreliable labels.
  In the case of unstructured (arbitrary) label noise, abstention during training
  enables the DAC to be used as an effective data cleaner by identifying samples that
  are likely to have label noise. We provide analytical results on the loss function
  behavior that enable dynamic adaption of abstention rates based on learning progress
  during training. We demonstrate the utility of the deep abstaining classifier for
  various image classification tasks under different types of label noise; in the
  case of arbitrary label noise, we show significant im- provements over previously
  published results on multiple image benchmarks.
layout: inproceedings
id: thulasidasan19a
tex_title: Combating Label Noise in Deep Learning using Abstention
firstpage: 6234
lastpage: 6243
page: 6234-6243
order: 6234
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Thulasidasan, Sunil and Bhattacharya, Tanmoy and Bilmes, Jeff and Chennupati,
  Gopinath and Mohd-Yusof, Jamal
author:
- given: Sunil
  family: Thulasidasan
- given: Tanmoy
  family: Bhattacharya
- given: Jeff
  family: Bilmes
- given: Gopinath
  family: Chennupati
- given: Jamal
  family: Mohd-Yusof
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
  link: http://proceedings.mlr.press/v97/thulasidasan19a/thulasidasan19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
