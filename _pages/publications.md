---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## [Fuzzy c-Means Clustering for Persistence Diagrams](https://arxiv.org/abs/2006.02796)

*Thomas O. M. Davies, Jack Aspinall, Bryan Wilder, Long Tran-Thanh*, arXiv:2006.02796, preprint (2020)

Persistence diagrams, a key tool in the field of Topological Data Analysis, concisely represent the topology of a point cloud. Most current methods to integrate persistence diagrams into machine learning either require prior knowledge of a ground-truth topology or map them into a feature vector, offering a trade-off between information loss and invoking the curse of dimensionality. In this paper we give an algorithm for Fuzzy c-Means (FCM) clustering directly on the space of persistence diagrams, enabling unsupervised learning that automatically captures the topological structure of data, with no prior knowledge or additional processing of persistence diagrams. We prove the same convergence guarantees as traditional FCM clustering: that any convergent subsequence of our algorithm tends to a local minimum or saddle point of the cost function. We end by presenting experiments that demonstrate our algorithm can successfully cluster transformed datasets from materials science where comparable Wasserstein barycentre clustering algorithms fail, whilst also running at least an order of magnitude faster. 