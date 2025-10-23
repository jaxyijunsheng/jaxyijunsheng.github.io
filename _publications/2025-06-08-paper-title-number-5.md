---
title: "Local Structure-Adaptive Graph Filtering for Collaborative Filtering"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is my thid work.'
date: 2025-02-17
venue: 'CIKM25'
paperurl: 'https://doi.org/10.1145/3746252.3761346'
citation: '<strong>Sheng, Y.</strong>, Lei, P. I.,  Liu, Y., Chen, X., & Gong, Z. (2025, October). "Local Structure-Adaptive Graph Filtering for Collaborative Filtering." In <i>Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM)</i>, in Press.'
---
***Abstract***

The structural heterogeneity of user-item interaction graphs poses a fundamental challenge for graph-based recommender systems. While Graph Convolutional Networks (GCNs) have achieved remarkable success in collaborative filtering, their uniform low-pass filtering nature often fails to accommodate the varying spectral needs of nodes with different local structures, resulting in suboptimal performance. To address this issue, we propose a Structurally Sensitive Adaptive Graph Filter, dubbed as SSAGF, a novel framework that enables structure-aware filtering on user-item graphs. SSAGF first clusters nodes based on local structural properties, then learns customized filters per group by reinterpreting the convolutional depth in GCNs. This adaptive mechanism ensures that nodes with distinct structural roles are treated appropriately, enhancing both accuracy and fairness without significantly increasing model complexity. To further improve scalability, SSAGF avoids costly eigenvalue decompositions by approximating spectral filters through Maclaurin series expansion, transforming the convolution into a pooling-like operation over standard GCN outputs. Extensive experiments on four benchmark datasets demonstrate that SSAGF consistently outperforms competitive baselines, especially in scenarios with high structural heterogeneity, offering a principled and efficient solution for structure-aware recommendation.
