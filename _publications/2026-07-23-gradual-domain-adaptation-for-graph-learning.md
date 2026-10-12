---
title: "Gradual Domain Adaptation for Graph Learning"
collection: publications
category: manuscripts
permalink: /publication/gradual-domain-adaptation-for-graph-learning
excerpt: 'This paper proposes a gradual domain adaptation framework for graph learning under large distribution shifts.'
date: 2026-07-23
venue: 'ACM TIST'
paperurl: 'https://doi.org/10.1145/3815185'
citation: 'Lei Pui Ieng, Chen Ximing, <strong>Sheng Yijun</strong>, Liu Yanyan, Gong Zhiguo*, & Yang Qiang. (2026). Gradual Domain Adaptation for Graph Learning. <i>ACM Transactions on Intelligent Systems and Technology</i>, 17(5), Article 112, pp. 1–45.'
---
***Abstract***

Existing machine learning literature lacks graph-based domain adaptation techniques capable of handling large distribution shifts, primarily due to the difficulty in simulating a coherent evolutionary path from source to target graph. To meet this challenge, we present a graph gradual domain adaptation (GGDA) framework, which constructs a compact domain sequence that minimizes information loss during adaptation. Our approach starts with an efficient generation of knowledge-preserving intermediate graphs over the Fused Gromov-Wasserstein (FGW) metric. A GGDA domain sequence is then constructed upon this bridging data pool through a novel vertex-based progression, which involves selecting “close” vertices and performing adaptive domain advancement to enhance inter-domain transferability. Theoretically, our framework provides implementable upper and lower bounds for the intractable inter-domain Wasserstein distance, enabling its flexible adjustment for optimal domain formation. Extensive experiments across diverse transfer scenarios demonstrate the superior performance of our GGDA framework. Our code is available at https://github.com/Louisa-LPI/GGDA.
