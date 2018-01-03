---
title: Fast interior-point inference in high-dimensional sparse, penalized state-space
  models
abstract: We present an algorithm for fast posterior inference in penalized high-dimensional
  state-space models, suitable in the case where a few measurements are taken in each
  time step. We assume that the state prior and observation likelihoods are log-concave
  and have a special structure that allows fast matrix-vector operations. We derive
  a second-order algorithm for computing the maximum a posteriori state path estimate,
  where the cost per iteration scales linearly both in time and memory. This is done
  by computing an approximate Newton direction using an efficient forward-backward
  scheme based on a sequence of low rank updates. We formalize the conditions under
  which our algorithm is applicable and prove its stability and convergence. We show
  that the state vector can be drawn from a large class of prior distributions without
  affecting the linear complexity of our algorithm. This class includes both Gaussian
  and nonsmooth sparse and group sparse priors for which we employ an interior point
  modification of our algorithm. We discuss applications in text modeling and neuroscience.
pdf: http://proceedings.mlr.press/v22/pnevmatikakis12/pnevmatikakis12.pdf
supplementary: http://proceedings.mlr.press/v22/pnevmatikakis12/pnevmatikakis12Supple.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: pnevmatikakis12
month: 0
tex_title: Fast interior-point inference in high-dimensional sparse, penalized state-space
  models
firstpage: 895
lastpage: 904
page: 895-904
order: 895
cycles: false
author:
- given: Eftychios
  family: Pnevmatikakis
- given: Liam
  family: Paninski
date: 2012-03-21
address: La Palma, Canary Islands
publisher: PMLR
container-title: Proceedings of the Fifteenth International Conference on Artificial
  Intelligence and Statistics
volume: '22'
genre: inproceedings
issued:
  date-parts:
  - 2012
  - 3
  - 21
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
