---
title: A General Framework for Structured Sparsity via Proximal Optimization
abstract: We study a generalized framework for structured sparsity. It extends the
  well-known methods of Lasso and Group Lasso by incorporating additional constraints
  on the variables as part of a convex optimization problem. This framework provides
  a straightforward way of favoring prescribed sparsity patterns, such as orderings,
  contiguous regions and overlapping groups, among others. Available optimization
  methods are limited to specific constraint sets and tend to not scale well with
  sample size and dimensionality.  We propose a first order proximal method, which
  builds upon results on fixed points and successive approximations. The algorithm
  can be applied to a general class of conic and norm constraints sets and relies
  on a proximity operator subproblem which can be computed numerically. Experiments
  on different regression problems demonstrate state-of-the art statistical performance,
  which improves over Lasso, Group Lasso and StructOMP. They also demonstrate the
  efficiency of the optimization algorithm and its scalability with the size of the
  problem.
pdf: http://proceedings.mlr.press/v22/baldassarre12/baldassarre12.pdf
layout: inproceedings
id: baldassarre12
month: 0
firstpage: 82
lastpage: 90
page: 82-90
sections: 
author:
- given: Luca
  family: Baldassarre
- given: Jean
  family: Morales
- given: Andreas
  family: Argyriou
- given: Massimiliano
  family: Pontil
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
