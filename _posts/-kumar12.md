---
title: Message-Passing Algorithms for MAP Estimation Using  DC Programming
abstract: We address the problem of finding the most likely assignment or MAP estimation
  in a Markov random field. We analyze the linear programming formulation of MAP through
  the lens of difference of convex functions (DC) programming, and use the concave-convex
  procedure (CCCP) to develop efficient message-passing solvers. The resulting algorithms
  are guaranteed to converge to a global optimum of the well-studied local polytope,
  an outer bound on the MAP marginal polytope. To tighten the outer bound, we show
  how to combine it with the mean-field based inner bound and, again, solve it using
  CCCP. We also identify a useful relationship between the DC formulations and some
  recently proposed algorithms based on Bregman divergence.  Experimentally, this
  hybrid approach produces optimal solutions for a range of hard OR problems and near-optimal
  solutions for standard benchmarks.
pdf: "./kumar12/kumar12.pdf"
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v22/kumar12/kumar12Supple.pdf
layout: inproceedings
key: kumar12
month: 0
firstpage: 656
lastpage: 664
origpdf: http://jmlr.org/proceedings/papers/v22/kumar12/kumar12.pdf
sections: 
authors:
- given: Akshat
  family: Kumar
- given: Shlomo
  family: Zilberstein
- given: Marc
  family: Toussaint
---
