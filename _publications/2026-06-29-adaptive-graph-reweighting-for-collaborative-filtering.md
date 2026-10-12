---
title: "Adaptive Graph Reweighting for Collaborative Filtering"
collection: publications
category: conferences
permalink: /publication/adaptive-graph-reweighting-for-collaborative-filtering
excerpt: 'This paper improves graph connectivity for collaborative filtering by adaptively reweighting edges.'
date: 2026-06-29
venue: 'WWW26'
paperurl: 'https://doi.org/10.1145/3774904.3792081'
citation: '<strong>Sheng Yijun</strong>, Chen Ximing, Lei Pui Ieng, Liu Yanyan, & Gong Zhiguo*. (2026). Adaptive Graph Reweighting for Collaborative Filtering. In <i>Proceedings of the ACM Web Conference (WWW)</i>, pp. 5710–5721.'
---
***Abstract***

Despite their success in Collaborative Filtering (CF), Graph Convolutional Networks (GCNs) are often viewed as Low-pass Graph Filters (LGFs) with task-specific supervision, while the influence of the underlying graph's spectral properties on LGF performance remains underexplored. Our analysis reveals that the performance of LGFs is strongly affected by algebraic connectivity. When connectivity is strong, LGFs tend to perform well; when it is weak, their effectiveness diminishes noticeably. This spectral sensitivity highlights an important limitation of existing models. To address this limitation, we propose Graph Booster, a learnable module that adaptively improves graph connectivity by reweighting edges. Unlike heuristic preprocessing, Graph Booster identifies bottleneck edges via spectral embeddings and adjusts their weights with a monotonic network guided by a lightweight graph connectivity regularizer. Integrated into LightGCN framework, our model BoostGCN achieves improvements over state-of-the-art methods, underscoring the significance of algebraic connectivity for graph-based CF.
