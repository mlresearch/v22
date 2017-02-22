---
title: Bayesian Classifier Combination
abstract: Bayesian model averaging linearly mixes the probabilistic predictions of
  multiple models, each weighted by its posterior probability. This is the coherent
  Bayesian way of combining multiple models only under certain restrictive assumptions,
  which we outline. We explore a general framework for Bayesian model combination
  (which differs from model averaging) in the context of classification. This framework
  explicitly models the relationship between each model's output and the unknown true
  label. The framework does not require that the models be probabilistic (they can
  even be human assessors), that they share prior information or receive the same
  training data, or that they be independent in their errors. Finally, the Bayesian
  combiner does not need to believe any of the models is in fact correct.  We test
  several variants of this classifier combination procedure starting from a classic
  statistical model proposed by Dawid and Skene (1979) and using MCMC to add more
  complex but important features to the model. Comparisons on several data sets to
  simpler methods like majority voting show that the Bayesian methods not only perform
  well but result in interpretable diagnostics on the data points and the models.
pdf: "./kim12/kim12.pdf"
layout: inproceedings
key: kim12
month: 0
firstpage: 619
lastpage: 627
origpdf: http://jmlr.org/proceedings/papers/v22/kim12/kim12.pdf
sections: 
authors:
- given: Hyun-Chul
  family: Kim
- given: Zoubin
  family: Ghahramani
---
