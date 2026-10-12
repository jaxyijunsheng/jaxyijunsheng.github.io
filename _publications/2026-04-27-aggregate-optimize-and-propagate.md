---
title: "Aggregate, Optimize, and Propagate: A Forward-Forward Algorithm Framework for Graph-Based Recommendation"
collection: publications
category: conferences
permalink: /publication/aggregate-optimize-and-propagate
excerpt: 'This paper proposes a Forward-Forward framework for graph-based recommendation.'
date: 2026-04-27
venue: 'DASFAA26'
paperurl: 'https://doi.org/10.1007/978-981-92-0375-8_25'
citation: 'Chen Ximing, Lei Pui Ieng, <strong>Sheng Yijun</strong>, Liu Yanyan, & Gong Zhiguo*. (2026, April). Aggregate, Optimize, and Propagate: A Forward-Forward Algorithm Framework for Graph-Based Recommendation. In <i>Database Systems for Advanced Applications (DASFAA)</i>, pp. 406–423.'
---
***Abstract***

Graph neural networks (GNNs) have shown exceptional performance in recommendation tasks. Prevailing graph recommendation models depend on message passing (MP) for aggregating node information, and backpropagation (BP) via chain rules for optimization. However, this combination risks under-trained nodes propagating incomplete or incorrect information to neighbors. Moreover, multi-layer aggregation further compounds these issues, leading to challenges such as over-smoothing and personalization loss. To address these limitations, we propose ForwardRec, a novel graph recommendation framework integrating the Forward-Forward (FF) algorithm with Hierarchical Rejection Sampling (HRS). The FF algorithm facilitates precise and comprehensive semantics by forward learning, while circumventing the drawbacks inherent to the aforementioned combination. Additionally, HRS utilizes rejection sampling within a hierarchical sampling process to ensure the generation of informative negative samples and computational efficiency. Crucially, the personalized preferences retrieved by FF enhance HRS’s capability to distinguish hard negatives from true positives. Meanwhile, due to the nuanced hard negatives, the optimization process in turn reduces the high-frequency noise induced by FF and helps each node become well-trained for further propagation. Theoretical analysis and extensive experiments demonstrate the superior efficacy and efficiency of ForwardRec for graph recommendation tasks.
