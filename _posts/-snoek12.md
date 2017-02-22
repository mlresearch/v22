---
title: On Nonparametric Guidance for Learning Autoencoder Representations
abstract: Unsupervised discovery of latent representations, in addition to being useful
  for density modeling, visualisation and exploratory data analysis, is also increasingly
  important for learning features relevant to discriminative tasks. Autoencoders,
  in particular, have proven to be an effective way to learn latent codes that reflect
  meaningful variations in data. A continuing challenge, however, is guiding an autoencoder
  toward representations that are useful for particular tasks. A complementary challenge
  is to find codes that are invariant to irrelevant transformations of the data. The
  most common way of introducing such problem-specific guidance in autoencoders has
  been through the incorporation of a parametric component that ties the latent representation
  to the label information. In this work, we argue that a preferable approach relies
  instead on a nonparametric guidance mechanism. Conceptually, it ensures that there
  exists a function that can predict the label information, without explicitly instantiating
  that function. The superiority of this guidance mechanism is confirmed on two datasets.
  In particular, this approach is able to incorporate invariance information (lighting,
  elevation, etc.) from the small NORB object recognition dataset and yields state-of-the-art
  performance for a single layer, non-convolutional network.
pdf: "./snoek12/snoek12.pdf"
layout: inproceedings
key: snoek12
month: 0
firstpage: 1073
lastpage: 1080
origpdf: http://jmlr.org/proceedings/papers/v22/snoek12/snoek12.pdf
sections: 
authors:
- given: Jasper
  family: Snoek
- given: Ryan
  family: Adams
- given: Hugo
  family: Larochelle
---
