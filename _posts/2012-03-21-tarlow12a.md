---
title: Structured Output Learning with High Order Loss Functions
abstract: Often when modeling structured domains, it is desirable to leverage information
  that is not naturally expressed  as simply a label. Examples include   knowledge
  about the evaluation measure that will be used at test time, and partial  (weak)
  label information. When the additional information has structure that factorizes
  according to small subsets of variables (i.e., is \emph{low order}, or \emph{decomposable}),  several
  approaches can be used to incorporate it into a learning procedure.   Our focus
  in this work is the more challenging case, where the additional information does
  not factorize according to low order graphical model structure; we call this the
  \emph{high order} case. We propose to formalize various forms of this additional
  information as high order loss functions, which may have complex interactions over
  large subsets of variables. We then address the computational challenges inherent
  in learning according to such loss functions, particularly focusing on the loss-augmented
  inference problem that arises in large margin learning; we show that learning with
  high order loss functions is often practical, giving strong empirical results, with
  one popular and several novel high-order loss functions, in several settings.
pdf: "./tarlow12a/tarlow12a.pdf"
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v22/tarlow12a/tarlow12aSupple.pdf
layout: inproceedings
key: tarlow12a
month: 0
firstpage: 1212
lastpage: 1220
origpdf: http://jmlr.org/proceedings/papers/v22/tarlow12a/tarlow12a.pdf
sections: 
authors:
- given: Daniel
  family: Tarlow
- given: Richard
  family: Zemel
---
