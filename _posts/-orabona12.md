---
title: Beyond Logarithmic Bounds in Online Learning
abstract: We prove logarithmic regret bounds that depend on the loss L_T^* of the
  competitor rather than on the number T of time steps. In the general online convex
  optimization setting,  our bounds hold for any smooth and exp-concave loss (such
  as the square loss or the logistic loss). This bridges the gap between the O(ln
  T) regret exhibited by exp-concave losses and the O(sqrt(L_T^*)) regret exhibited
  by smooth losses. We also show that these bounds are tight for specific losses,
  thus they cannot be improved in general. For online regression with square loss,
  our analysis can be used to derive a sparse randomized variant of the online Newton
  step, whose expected number of updates scales with the algorithm's loss. For online
  classification, we prove the first logarithmic mistake bounds that do not rely on
  prior knowledge of a bound on the competitor's norm.
pdf: "./orabona12/orabona12.pdf"
layout: inproceedings
key: orabona12
month: 0
firstpage: 823
lastpage: 831
origpdf: http://jmlr.org/proceedings/papers/v22/orabona12/orabona12.pdf
sections: 
authors:
- given: Francesco
  family: Orabona
- given: Nicolo
  family: Cesa-Bianchi
- given: Claudio
  family: Gentile
---
