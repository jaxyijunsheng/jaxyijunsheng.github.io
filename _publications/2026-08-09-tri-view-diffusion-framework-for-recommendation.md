---
title: "Towards A Tri-View Diffusion Framework for Recommendation"
collection: publications
category: conferences
permalink: /publication/tri-view-diffusion-framework-for-recommendation
excerpt: 'This paper studies diffusion-based recommendation through energy, entropy, and hard-negative sampling.'
date: 2026-08-09
venue: 'KDD26'
paperurl: 'https://doi.org/10.1145/3770854.3780157'
citation: 'Chen Ximing, Lei Pui Ieng, <strong>Sheng Yijun</strong>, Liu Yanyan, & Gong Zhiguo*. (2026, August). Towards A Tri-View Diffusion Framework for Recommendation. In <i>Proceedings of the 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)</i>, pp. 116–127.'
---
***Abstract***

Diffusion models (DMs) have recently gained significant interest for their exceptional potential in recommendation tasks. This stems primarily from their prominent capability in distilling, modeling, and generating comprehensive user preferences. However, previous work fails to examine DMs in recommendation tasks through a rigorous lens. In this paper, we first experimentally investigate the completeness of recommender models from a thermodynamic view. We reveal that existing DM-based recommender models operate by maximizing the energy, while classic recommender models operate by reducing the entropy. Based on this finding, we propose a minimalistic diffusion framework that incorporates both factors via the maximization of Helmholtz free energy. Meanwhile, to foster the optimization, our reverse process is armed with a well-designed denoiser to maintain the inherent anisotropy, which measures the user-item cross-correlation in the context of bipartite graphs. Finally, we adopt an Acceptance-Rejection Gumbel Sampling Process (AR-GSP) to prioritize the far-outnumbered unobserved interactions for model robustness. AR-GSP integrates an acceptance-rejection sampling to ensure high-quality hard negative samples for general recommendation tasks, and a timestep-dependent Gumbel Softmax to handle an adaptive sampling strategy for diffusion models. Theoretical analyses and extensive experiments demonstrate that our proposed framework has distinct superiority over baselines in terms of accuracy and efficiency.
