---
title: Approximate Inference by Intersecting Semidefinite Bound and Local Polytope
abstract: 'Inference in probabilistic graphical models can be represented as a constrained
  optimization problem of a free-energy functional. Substantial research has been
  focused on the approximation of the constraint set, also known as the marginal polytope.
  This paper presents a novel inference algorithm that tightens and solves the optimization
  problem by intersecting the popular local polytope and the semidefinite outer bound
  of the marginal polytope. Using dual decomposition, our method separates the optimization
  problem into two subproblems: a semidefinite program (SDP), which is solved by a
  low-rank SDP algorithm, and a free-energy based optimization problem, which is solved
  by convex belief propagation. Our method has a very reasonable computational complexity
  and its actual running time is typically within a small factor (=10) of convex belief
  propagation. Tested on both synthetic data and a real-world protein side-chain packing
  benchmark, our method significantly outperforms tree-reweighted belief propagation
  in both marginal probability inference and MAP inference.  Our method is competitive
  with the state-of-the-art in MRF inference, solving all protein tasks solved by
  the recently presented MPLP method, and beating MPLP on lattices with strong edge
  potentials.'
pdf: "./peng12/peng12.pdf"
layout: inproceedings
key: peng12
month: 0
firstpage: 868
lastpage: 876
origpdf: http://jmlr.org/proceedings/papers/v22/peng12/peng12.pdf
sections: 
authors:
- given: Jian
  family: Peng
- given: Tamir
  family: Hazan
- given: Nathan
  family: Srebro
- given: Jinbo
  family: Xu
---
