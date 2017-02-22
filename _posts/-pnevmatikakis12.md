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
pdf: "./pnevmatikakis12/pnevmatikakis12.pdf"
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v22/pnevmatikakis12/pnevmatikakis12Supple.pdf
layout: inproceedings
key: pnevmatikakis12
month: 0
firstpage: 895
lastpage: 904
origpdf: http://jmlr.org/proceedings/papers/v22/pnevmatikakis12/pnevmatikakis12.pdf
sections: 
authors:
- given: Eftychios
  family: Pnevmatikakis
- given: Liam
  family: Paninski
---
