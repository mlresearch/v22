---
title: Nonlinear low-dimensional regression using auxiliary coordinates
abstract: When doing regression with inputs and outputs that are high-dimensional,
  it often makes sense to reduce the dimensionality of the inputs before mapping to
  the outputs. Much work in statistics and machine learning, such as reduced-rank
  regression, slice inverse regression and their variants, has focused on linear dimensionality
  reduction, or on estimating the dimensionality reduction first and then the mapping.
  We propose a method where both the dimensionality reduction and the mapping can
  be nonlinear and are estimated jointly. Our key idea is to define an objective function
  where the low-dimensional coordinates are free parameters, in addition to the dimensionality
  reduction and the mapping. This has the effect of decoupling many groups of parameters
  from each other, affording a far more effective optimization than if using a deep
  network with nested mappings, and to use a good initialization from slice inverse
  regression or spectral methods. Our experiments with image and robot applications
  show our approach to improve over direct regression and various existing approaches.
pdf: "./wang12/wang12.pdf"
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v22/wang12/wang12Supple.tgz
layout: inproceedings
key: wang12
month: 0
firstpage: 1295
lastpage: 1304
origpdf: http://jmlr.org/proceedings/papers/v22/wang12/wang12.pdf
sections: 
authors:
- given: Weiran
  family: Wang
- given: Miguel
  family: Carreira-Perpinan
---
