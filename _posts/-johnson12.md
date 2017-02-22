---
title: High-dimensional Sparse Inverse Covariance Estimation using Greedy Methods
abstract: In this paper we consider the task of estimating the non-zero pattern of
  the sparse inverse covariance matrix of a zero-mean Gaussian random vector from
  a set of iid samples. Note that this is also equivalent to recovering the underlying
  graph structure of a sparse Gaussian Markov Random Field (GMRF).  We present two
  novel greedy approaches to solving this problem.  The first estimates the non-zero
  covariates of the overall inverse covariance matrix using a series of global forward
  and backward greedy steps.  The second estimates the neighborhood of each node in
  the graph separately, again using greedy forward and backward steps, and combines
  the intermediate neighborhoods to form an overall estimate. The principal contribution
  of this paper is a rigorous analysis of the sparsistency, or consistency in recovering
  the sparsity pattern of the inverse covariance matrix. Surprisingly, we show that
  both the local and global greedy methods learn the full structure of the model with
  high probability given just O(d log(p)) samples, which is a significant improvement
  over state of the art L1-regularized Gaussian MLE (Graphical Lasso) that requires
  O(d^2 log(p)) samples. Moreover, the restricted eigenvalue and smoothness conditions
  imposed by our greedy methods are much weaker than the strong irrepresentable conditions
  required by the L1-regularization based methods. We corroborate our results with
  extensive simulations and examples, comparing our local and global greedy methods
  to the L1-regularized Gaussian MLE as well as the nodewise L1-regularized linear
  regression (Neighborhood Lasso).
pdf: "./johnson12/johnson12.pdf"
layout: inproceedings
key: johnson12
month: 0
firstpage: 574
lastpage: 582
origpdf: http://jmlr.org/proceedings/papers/v22/johnson12/johnson12.pdf
sections: 
authors:
- given: Christopher
  family: Johnson
- given: Ali
  family: Jalali
- given: Pradeep
  family: Ravikumar
---
