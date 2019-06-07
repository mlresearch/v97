---
title: 'POLITEX: Regret Bounds for Policy Iteration using Expert Prediction'
booktitle: Proceedings of the 36th International Conference on Machine Learning
year: '2019'
volume: '97'
address:
series: Proceedings of Machine Learning Research
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v97/abbasi-yadkori19a/abbasi-yadkori19a.pdf
url: http://proceedings.mlr.press/v97/abbasi-yadkori19a.html
abstract: We present POLITEX (POLicy ITeration with EXpert advice), a variant of policy
  iteration where each policy is a Boltzmann distribution over the sum of action-value
  function estimates of the previous policies, and analyze its regret in continuing
  RL problems. We assume that the value function error after running a policy for
  $\tau$ time steps scales as $\epsilon(\tau) = \epsilon_0 + O(\sqrt{d/\tau})$, where $\epsilon_0$
  is the worst-case approximation error and $d$ is the number of features in a compressed
  representation of the state-action space. We establish that this condition is satisfied
  by the LSPE algorithm under certain assumptions on the MDP and policies. Under the
  error assumption, we show that the regret of POLITEX in uniformly mixing MDPs scales
  as $O(d^{1/2}T^{3/4} + \epsilon_0T)$, where $O(\cdot)$ hides logarithmic terms and problem-dependent
  constants. Thus, we provide the first regret bound for a fully practical model-free
  method which only scales in the number of features, and not in the size of the underlying
  MDP. Experiments on a queuing problem confirm that POLITEX is competitive with some
  of its alternatives, while preliminary results on Ms Pacman (one of the standard
  Atari benchmark problems) confirm the viability of POLITEX beyond linear function
  approximation.
layout: inproceedings
id: abbasi-yadkori19a
tex_title: "{POLITEX}: Regret Bounds for Policy Iteration using Expert Prediction"
firstpage: 3692
lastpage: 3702
page: 3692-3702
order: 3692
cycles: false
bibtex_editor: Chaudhuri, Kamalika and Salakhutdinov, Ruslan
editor:
- given: Kamalika
  family: Chaudhuri
- given: Ruslan
  family: Salakhutdinov
  bibtex_author: Abbasi-Yadkori, Yasin and Bartlett, Peter and Bhatia, Kush and Lazic, Nevena and Szepesvari, Csaba and Weisz, Gellert
  author:
  - given: Yasin
    family: Abbasi-Yadkori
  - given: Peter
    family: Bartlett
  - given: Kush
    family: Bhatia
  - given: Nevena
    family: Lazic
  - given: Csaba
    family: Szepesvari
  - given: Gellert
    family: Weisz
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
  link: http://proceedings.mlr.press/v97/abbasi-yadkori19a/abbasi-yadkori19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
