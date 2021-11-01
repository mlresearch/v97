---
title: Universal Multi-Party Poisoning Attacks
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address: 
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/mahloujifar19a/mahloujifar19a.pdf
url: http://proceedings.mlr.press/v97/mahloujifar19a.html
abstract: In this work, we demonstrate universal multi-party poisoning attacks that
  adapt and apply to any multi-party learning process with arbitrary interaction pattern
  between the parties. More generally, we introduce and study $(k,p)$-poisoning attacks
  in which an adversary controls $k\in[m]$ of the parties, and for each corrupted
  party $P_i$, the adversary submits some poisoned data $T’_i$ on behalf of $P_i$
  that is still "$(1-p)$-close" to the correct data $T_i$ (e.g., $1-p$ fraction of
  $T’_i$ is still honestly generated).We prove that for any "bad" property $B$ of
  the final trained hypothesis $h$ (e.g., $h$ failing on a particular test example
  or having "large" risk) that has an arbitrarily small constant probability of happening
  without the attack, there always is a $(k,p)$-poisoning attack that increases the
  probability of $B$ from $\mu$ to by $\mu^{1-p \cdot k/m} = \mu + \Omega(p \cdot
  k/m)$. Our attack only uses clean labels, and it is online, as it only knows the
  the data shared so far.
layout: inproceedings
id: mahloujifar19a
tex_title: Universal Multi-Party Poisoning Attacks
firstpage: 4274
lastpage: 4283
page: 4274-4283
order: 4274
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
bibtex_author: Mahloujifar, Saeed and Mahmoody, Mohammad and Mohammed, Ameer
author:
- given: Saeed
  family: Mahloujifar
- given: Mohammad
  family: Mahmoody
- given: Ameer
  family: Mohammed
date: 2019-05-24
container-title: Proceedings of the 36th International Conference on Machine Learning
genre: inproceedings
issued:
  date-parts:
  - 2019
  - 5
  - 24
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
