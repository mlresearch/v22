---
title: Classifier Cascade for Minimizing Feature Evaluation Cost
abstract: Machine learning algorithms are increasingly used in large-scale industrial
  settings. Here, the operational cost during test-time has to be taken into account
  when an algorithm is designed.  This operational cost is affected by the average
  running time and the computation time required for feature extraction. When a diverse
  set of features is used, the  latter can vary drastically. In this paper we propose
  an algorithm that constructs a cascade of classifiers that explicitly trades-off
  operational cost and classifier accuracy while accounting for on-demand feature
  extraction costs. Different from previous work, our algorithm re-optimizes trained
  classifiers and allows expensive features to be scheduled at any stage within the
  cascade to minimize overall cost. Experiments on actual web-search ranking data
  sets demonstrate that our framework leads to drastic test-time improvements.
pdf: "./chen12c/chen12c.pdf"
layout: inproceedings
key: chen12c
month: 0
firstpage: 218
lastpage: 226
origpdf: http://jmlr.org/proceedings/papers/v22/chen12c/chen12c.pdf
sections: 
authors:
- given: Minmin
  family: Chen
- given: Zhixiang
  family: Xu
- given: Kilian
  family: Weinberger
- given: Olivier
  family: Chapelle
- given: Dor
  family: Kedem
---
