---
title: A Semi-Supervised Methodology for Fishing Activity Detection Using the Geometry
  behind the Trajectory of Multiple Vessels
authors:
- M. D. Ferreira
- Gabriel Spadon
- Amílcar Soares
- S. Matwin
date: '2022-01-01'
publishDate: '2024-06-23T19:22:55.431509Z'
publication_types:
- article-journal
publication: '*Sensors*'
doi: 10.3390/s22166063
abstract: Automatic Identification System (AIS) messages are useful for tracking vessel
  activity across oceans worldwide using radio links and satellite transceivers. Such
  data play a significant role in tracking vessel activity and mapping mobility patterns
  such as those found during fishing activities. Accordingly, this paper proposes
  a geometric-driven semi-supervised approach for fishing activity detection from
  AIS data. Through the proposed methodology, it is shown how to explore the information
  included in the messages to extract features describing the geometry of the vessel
  route. To this end, we leverage the unsupervised nature of cluster analysis to label
  the trajectory geometry, highlighting changes in the vessel’s moving pattern, which
  tends to indicate fishing activity. The labels obtained by the proposed unsupervised
  approach are used to detect fishing activities, which we approach as a time-series
  classification task. We propose a solution using recurrent neural networks on AIS
  data streams with roughly 87% of the overall F-score on the whole trajectories of
  50 different unseen fishing vessels. Such results are accompanied by a broad benchmark
  study assessing the performance of different Recurrent Neural Network (RNN) architectures.
  In conclusion, this work contributes by proposing a thorough process that includes
  data preparation, labeling, data modeling, and model validation. Therefore, we present
  a novel solution for mobility pattern detection that relies upon unfolding the geometry
  observed in the trajectory.
links:
- name: URL
  url: https://www.semanticscholar.org/paper/0f47a5797fc4c5e11b672053b226b0699b19096a
---