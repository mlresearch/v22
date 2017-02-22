---
title: Scalable Inference on Kingman's Coalescent using Pair Similarity
abstract: We present a scalable sequential Monte Carlo algorithm and its greedy counterpart
  for models based on Kingman's coalescent. We utilize fast nearest neighbor algorithms
  to limit expensive computations to only a subset of data point pairs. For a dataset
  size of n, the resulting algorithm has O(n log n) computational complexity.  We
  empirically verify that we achieve a large speedup in computation. When the gain
  in speed is used for increasing the number of particles, we  can often  obtain significantly
  better samples than those of previous algorithms.  We apply our algorithm for learning
  visual taxonomies of birds on 6033 examples, a dataset size for which previous algorithms
  fail to be feasible.
pdf: "./gorur12/gorur12.pdf"
supplementary: Supplementary:http://jmlr.org/proceedings/papers/v22/gorur12/gorur12Supple.pdf
layout: inproceedings
key: gorur12
month: 0
firstpage: 440
lastpage: 448
origpdf: http://jmlr.org/proceedings/papers/v22/gorur12/gorur12.pdf
sections: 
authors:
- given: Dilan
  family: Gorur
- given: Levi
  family: Boyles
- given: Max
  family: Welling
---
