---
title: Efficient Gaussian Process Inference for Short-Scale Spatio-Temporal Modeling
abstract: This paper presents an efficient Gaussian process inference scheme for modeling
  shortscale phenomena in spatio-temporal datasets. Our model uses a sum of separable,
  compactly supported covariance functions, which yields a full covariance matrix
  represented in terms of small sparse matrices operating either on the spatial or
  temporal domain. The proposed inference procedure is based on Gibbs sampling, in
  which samples from the conditional distribution of the latent function values are
  obtained by applying a simple linear transformation to samples drawn from the joint
  distribution of the function values and the observations. We make use of the proposed
  model structure and the conjugate gradient method to compute the required transformation.
  In the experimental part, the proposed algorithm is compared to the standard approach
  using the sparse Cholesky decomposition and it is shown to be much faster and computationally
  feasible for 100-1000 times larger datasets. We demonstrate the advantages of the
  proposed method in the problem of reconstructing sea surface temperature, which
  requires processing of a real-world dataset with 10^6 observations.
pdf: "./luttinen12/luttinen12.pdf"
layout: inproceedings
key: luttinen12
month: 0
firstpage: 741
lastpage: 750
origpdf: http://jmlr.org/proceedings/papers/v22/luttinen12/luttinen12.pdf
sections: 
authors:
- given: Jaakko
  family: Luttinen
- given: Alexander
  family: Ilin
---
