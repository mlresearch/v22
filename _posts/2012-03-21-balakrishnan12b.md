---
title: 'Scalable Personalization of Long-Term Physiological Monitoring: Active Learning
  Methodologies for Epileptic Seizure Onset Detection'
abstract: Patient-specific algorithms to detect adverse clinical events during long-term
  physiological monitoring substantially improve performance relative to patient-nonspecific
  ones. However, these algorithms often rely on the availability of expert hand-labeled
  data for training, which severely restricts the scalability of personalized monitoring
  within a real-world setting. While active learning offers a natural framework to
  address this issue, the relative merits of different active learning methodologies
  have not been extensively studied in the setting of developing clinically useful
  detectors for infrequent time-series events. In this paper, we identify a core set
  of principles that are relative to the specific goal of personalized long-term physiological
  monitoring. We describe and compare different approaches for initialization, batch
  selection and termination within the active learning process. We position this work
  in the context of epileptic seizure onset detection. When evaluated on a database
  of scalp EEG recordings from 23 epileptic patients, we show that a  combined distance-
  and diversity-based measure to determine the data to be queried, max-min clustering
  for identification of the initialization set, and a comparison of consecutive support
  vector sets to guide termination results in an active learning-based detector that
  can achieve similar performance to a patient-specific detector while requiring two
  orders of magnitude fewer labeled examples for training.
pdf: http://proceedings.pmlr.press/balakrishnan12b/balakrishnan12b.pdf
layout: inproceedings
id: balakrishnan12b
month: 0
firstpage: 73
lastpage: 81
page: 73-81
origpdf: http://jmlr.org/proceedings/papers/v22/balakrishnan12b/balakrishnan12b.pdf
sections: 
author:
- given: Guha
  family: Balakrishnan
- given: Zeeshan
  family: Syed
date: 2012-03-21
address: La Palma, Canary Islands
publisher: PMLR
container-title: Proceedings of the Fifteenth International Conference on Artificial
  Intelligence and Statistics
volume: '22'
genre: inproceedings
issued:
  date-parts:
  - 2012
  - 3
  - 21
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
