---
title: Online Clustering with Experts
abstract: Approximating the k-means clustering objective with an online learning algorithm
  is an open problem. We introduce a family of online clustering algorithms by extending
  algorithms for online supervised learning, with access to expert predictors, to
  the unsupervised learning setting. Instead of computing prediction errors in order
  to re-weight the experts, the algorithms compute an approximation to the current
  value of the k-means objective obtained by each expert.  When the experts are batch
  clustering algorithms with b-approximation guarantees with respect to the k-means
  objective (for example, the k-means++ or k-means# algorithms), applied to a sliding
  window of the data stream, our algorithms obtain approximation guarantees with respect
  to the k-means objective. The form of these online clustering approximation guarantees
  is novel, and extends an evaluation framework proposed by Dasgupta as an analog
  to regret. Notably, our approximation bounds are with respect to the optimal k-means
  cost on the entire data stream seen so far, even though the algorithm is online.
  Our algorithm’s empirical performance tracks that of the best clustering algorithm
  in its expert set.
pdf: http://proceedings.mlr.press/v22/choromanska12/choromanska12.pdf
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v22/choromanska12/choromanska12Supple.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: choromanska12
month: 0
tex_title: Online Clustering with Experts
firstpage: 227
lastpage: 235
page: 227-235
sections: 
author:
- given: Anna
  family: Choromanska
- given: Claire
  family: Monteleoni
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
