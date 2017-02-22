---
title: Exploiting Unrelated Tasks in Multi-Task Learning
abstract: We study the problem of learning a group of principal tasks using a group
  of auxiliary tasks, unrelated to the principal ones. In many applications, joint
  learning of unrelated tasks which use the same input data can be beneficial. The
  reason is that prior knowledge about which tasks are unrelated can lead to sparser
  and more informative representations for each task, essentially screening out idiosyncrasies
  of the data distribution. We propose a novel method which builds on a prior multitask
  methodology by favoring a shared low dimensional  representation within each group
  of tasks. In addition, we impose a penalty on tasks from different groups which
  encourages the two representations to be orthogonal. We further discuss a condition
  which ensures convexity of the optimization problem and argue that it can be solved
  by alternating minimization. We present experiments on synthetic and real data,
  which indicate that incorporating unrelated tasks can improve significantly over
  standard multi-task learning methods.
pdf: "./romera12/romera12.pdf"
layout: inproceedings
key: romera12
month: 0
firstpage: 951
lastpage: 959
origpdf: http://jmlr.org/proceedings/papers/v22/romera12/romera12.pdf
sections: 
authors:
- given: Bernardino Romera
  family: Paredes
- given: Andreas
  family: Argyriou
- given: Nadia
  family: Berthouze
- given: Massimiliano
  family: Pontil
---
