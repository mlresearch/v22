---
title: Lifted Linear Programming
abstract: Lifted inference approaches have rendered large, previously intractable
  probabilistic inference problems quickly solvable by handling whole sets of indistinguishable
  objects together. Triggered by this success, we show that another important AI technique
  is liftable, too, namely linear programming.  Intuitively, given a linear program
  (LP), we employ a lifted variant of Gaussian belief propagation (GaBP) to solve
  the systems of linear equations arising when running an interior-point method to
  solve the LP.   However, this naive solution cannot make use of standard solvers
  for linear equations and is doomed to construct lifted networks in each iteration
  of the interior-point method again,  an operation that can itself be quite costly.
  To address both issues, we show how to read off an equivalent LP from the lifted
  GaBP computations that can be solved using any off-the-shelf LP solver. We prove
  the correctness of this compilation approach, including a lifted duality theorem,
  and experimentally demonstrate that it can greatly reduce the cost of solving LPs.
pdf: "./mladenov12/mladenov12.pdf"
layout: inproceedings
key: mladenov12
month: 0
firstpage: 788
lastpage: 797
origpdf: http://jmlr.org/proceedings/papers/v22/mladenov12/mladenov12.pdf
sections: 
authors:
- given: Martin
  family: Mladenov
- given: Babak
  family: Ahmadi
- given: Kristian
  family: Kersting
---
