---
title: "Dual graph collaborative filtering"
collection: publications
category: manuscripts
permalink: /publication/dual-graph-collaborative-filtering
excerpt: 'This paper models both interest and disinterest collaborative signals for graph-based recommendation.'
date: 2026-06-12
venue: 'Knowledge and Information Systems'
paperurl: 'https://doi.org/10.1007/s10115-026-02796-0'
citation: '<strong>Sheng Yijun</strong>, Liu Yanyan, Lei Pui Ieng, Chen Ximing, & Gong Zhiguo*. (2026). Dual graph collaborative filtering. <i>Knowledge and Information Systems</i>, 68(1), 182.'
---
***Abstract***

Graph neural network (GNN) is one of the most prevalent deep learning Collaborative Filtering (CF) methods in recent years, owing to its powerful capacity to model graph neighborhood dependencies. For recommendation systems, GNN captures the preference of users by propagating messages through observed interactions. However, most existing recommendation models merely focus on collaborative signals between users who prefer the same item (interest-CF signals), while ignoring the signals between users who show no interest in the same item (disinterest-CF signals). In this work, we incorporate both interest and disinterest collaborative signals and devise a novel Dual Graph Collaborative Filtering. In DGCF, alongside the original user–item interaction graph, we construct an additional graph with disinterest item sampling, which is used to generate disinterest collaborative signals by embedding differentials. By performing convolutions on the interest graph and novel deconvolutions on the disinterest graph, we explicitly learn two types of signals. To reduce noise in the dual graphs, we propose a dual latent graph learning module that dynamically updates the two graph structures during training, enhancing robustness. Finally, we employ a contrastive learning framework to align the representation of the dual views. Extensive experiments were conducted on three widely used benchmark datasets, verifying the superiority of our model compared with state-of-the-art approaches.
