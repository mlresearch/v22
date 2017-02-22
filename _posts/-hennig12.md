---
title: Kernel Topic Models
abstract: Latent Dirichlet Allocation models discrete data as a mixture of discrete
  distributions, using Dirichlet beliefs over the mixture weights. We study a variation
  of this concept, in which the documents' mixture weight beliefs are replaced with
  squashed Gaussian distributions. This allows documents to be associated with elements
  of a Hilbert space, admitting kernel topic models (KTM), modelling temporal, spatial,
  hierarchical, social and other structure between documents. The main challenge is
  efficient approximate inference on the latent Gaussian. We present an approximate
  algorithm cast around a Laplace approximation in a transformed basis. The KTM can
  also be interpreted as a type of Gaussian process latent variable model, or as a
  topic model conditional on document features, uncovering links between earlier work
  in these areas.
pdf: "./hennig12/hennig12.pdf"
layout: inproceedings
key: hennig12
month: 0
firstpage: 511
lastpage: 519
origpdf: http://jmlr.org/proceedings/papers/v22/hennig12/hennig12.pdf
sections: 
authors:
- given: Philipp
  family: Hennig
- given: David
  family: Stern
- given: Ralf
  family: Herbrich
- given: Thore
  family: Graepel
---
