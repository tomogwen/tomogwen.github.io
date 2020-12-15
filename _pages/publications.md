---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## [Hypothesis classes with a unique persistence diagram are nonuniformly learnable](https://openreview.net/pdf?id=Ay-RgChnje)

*Nicholas Bishop, Thomas Davies, Long Tran-Thanh*, arXiv:2006.02796, Spotlight paper at TDA and Beyond workshop at NeurIPS 2020.

Persistence-based summaries are increasingly integrated into deep learning through topological loss functions or regularisers. The implicit role of a topological term in a loss function is to restrict the class of functions in which we are learning (the hypothesis class) to those with a specific topology.  Although doing so has had empirical success, to the best of our knowledge there exists no result in the literature that theoretically justifies this restriction.  Given a binary classifier in the plane with a Morse-like decision boundary, we prove that the hypothesis class defined by restricting the topology of the possible decision boundaries to those with a unique persistence diagram results in a nonuniformly learnable class of functions. In doing so, we provide a statistical learning theoretic justification for the use of persistence-based summaries in loss functions.

## [Fuzzy c-Means Clustering for Persistence Diagrams](https://arxiv.org/abs/2006.02796)

*Thomas Davies, Jack Aspinall, Bryan Wilder, Long Tran-Thanh*, arXiv:2006.02796, TDA and Beyond workshop at NeurIPS 2020.

Persistence diagrams concisely represent the topology of a point cloud whilst having strong theoretical guarantees. Most current approaches to integrating topological information into machine learning implicitly map persistence diagrams to a Hilbert space, resulting in deformation of the underlying metric structure whilst also generally requiring prior knowledge about the true topology of the space. In this paper we give an algorithm for Fuzzy c-Means (FCM) clustering directly on the space of persistence diagrams, enabling unsupervised learning that automatically captures the topological structure of data, with no prior knowledge or additional processing of persistence diagrams. We prove the same convergence guarantees as traditional FCM clustering: every convergent subsequence of iterates tends to a local minimum or saddle point. We end by presenting experiments where our fuzzy topological clustering algorithm allows for unsupervised top-$k$ candidate selection in settings where (i) the properties of persistence diagrams make them the natural choice over geometric equivalents, and (ii) the probabilistic membership values let us rank candidates in settings where verifying candidate suitability is expensive: lattice structure classification in materials science and pre-trained model selection in machine learning.