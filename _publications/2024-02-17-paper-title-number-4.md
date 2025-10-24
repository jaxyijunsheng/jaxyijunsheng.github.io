---
title: "Learning Invariant Reliability under Diverse Contexts for Robust Multimedia Recommendation"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is my second work.'
date: 2025-02-17
venue: 'CIKM25'
paperurl: 'https://doi.org/10.1145/3746252.3761262'
citation: '<strong>Sheng Yijun</strong>, Lei Pui Ieng, Liu Yanyan, Chen Ximing, & Gong Zhiguo*. (2025, October). Learning Invariant Reliability under Diverse Contexts for Robust Multimedia Recommendation. In <i>Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM)</i>, in Press.'
---
***Abstract***

In graph-based multimedia recommendation, accurately modeling item-item semantic similarity is crucial for constructing high-quality semantic structures. However, multimodal content often exhibits semantic inconsistencies across modalities, resulting in noisy or misleading similarity signals. We refer to this as modality mismatching, where unaligned representations, such as an image conveying semantics unrelated to its accompanying text, undermine the reliability of feature-based similarity estimation. Importantly, modality consistency is context sensitive, varying with the underlying semantic environment in which modalities are interpreted. This highlights the necessity of jointly modeling modality reliability and contextual semantics. To address this challenge, we propose RGSLMRec, a robust graph structure learning framework that models and exploits the semantic reliability of multimodal features under diverse contexts. At its core, RGSLMRec builds on the invariant learning paradigm and introduces two key innovations: (i) it simulates multiple perturbed semantic environments and employs environment-specific monotonic networks to estimate reliability; and (ii) it adopts a risk-invariant objective based on Variance Risk Extrapolation to enforce the learning of invariant reliability across environments. On top of this, (iii) RGSLMRec constructs reliability-guided item-item graphs and captures collaborative and semantic signals via a hybrid early-late fusion strategy.
Extensive experiments on several real-world datasets and additional synthetically perturbed datasets demonstrate that RGSLMRec not only outperforms strong baselines but also exhibits superior robustness to modality mismatching.