---
title: 'Domain Adaptation: A Small Sample Statistical Approach'
abstract: We study the prevalent problem when a test distribution differs from the
  training distribution. We consider a setting where our training set consists of
  a small number of sample domains, but where we have many samples in each domain.
  Our goal is to generalize to a new domain. For example, we may want to learn a similarity
  function using only certain classes of objects, but we desire that this similarity
  function be applicable to object classes not present in our training sample (e.g.
  we might seek to learn that ``dogs are similar to dogs'' even though images of dogs
  were absent from our training set). Our theoretical analysis shows that we can select
  many more features than domains while avoiding overfitting by utilizing data-dependent
  variance properties. We present a greedy feature selection algorithm based on using
  T-statistics. Our experiments validate this theory showing that our T-statistic
  based greedy feature selection is more robust at avoiding overfitting than the classical
  greedy procedure.
pdf: "./salakhutdinov12/salakhutdinov12.pdf"
layout: inproceedings
id: salakhutdinov12
month: 0
firstpage: 960
lastpage: 968
page: 960-968
origpdf: http://jmlr.org/proceedings/papers/v22/salakhutdinov12/salakhutdinov12.pdf
sections: 
author:
- given: Ruslan
  family: Salakhutdinov
- given: Sham
  family: Kakade
- given: Dean
  family: Foster
date: '2012-03-21 00:16:00'
publisher: PMLR
---
