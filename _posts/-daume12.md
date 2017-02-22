---
title: Protocols for Learning Classifiers on Distributed Data
abstract: We consider the problem of learning classifiers for labeled data that has
  been distributed across several nodes. Our goal is to find a single classifier,
  with small approximation error, across all datasets while minimizing the communication
  between nodes. This setting models real-world communication bottlenecks in the processing
  of massive distributed datasets. We present several very general sampling-based
  solutions as well as some two-way protocols which have a provable exponential speed-up
  over any one-way protocol. We focus on core problems for noiseless data distributed
  across two or more nodes. The techniques we introduce are reminiscent of active
  learning, but rather than actively probing labels, nodes actively communicate with
  each other, each node simultaneously learning the important data from another node.
pdf: "./daume12/daume12.pdf"
layout: inproceedings
key: daume12
month: 0
firstpage: 282
lastpage: 290
origpdf: http://jmlr.org/proceedings/papers/v22/daume12/daume12.pdf
sections: 
authors:
- given: Hal Daume
  family: III
- given: Jeff
  family: Phillips
- given: Avishek
  family: Saha
- given: Suresh
  family: Venkatasubramanian
---
