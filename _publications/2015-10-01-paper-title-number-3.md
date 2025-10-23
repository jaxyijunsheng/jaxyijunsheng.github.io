---
title: "Social influence learning for recommendation systems."
collection: publications
category: conferences
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is done by my junior colleague Simon.'
date: 2024-10-01
venue: 'CIKM24'
slidesurl: #'https://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3627673.3679598'
citation: 'Chen, X., Lei, P. I., <strong>Sheng, Y.</strong>, Liu, Y., & Gong, Z. (2024, October). "Social influence learning for recommendation systems." In <i>Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM)</i>, pp. 312–322.'
---
***Abstract***

Social recommendation systems leverage the social relations among users to deal with the inherent cold-start problem in user-item interactions. However, previous models only treat the social graph as the static auxiliary to the user-item interaction graph, rather than dig out the hidden essentials and optimize them for better recommendations. Thus, the potential of social influence is still under-explored. In this paper, we will fill this gap by proposing a novel model for social influence learning to derive the essential influence patterns within the user relationships. Our model views the social influence from the perspectives of (1) the diversity of neighborhood's influence on the users, (2) the disentanglement of neighborhood's influence on the users, and (3) the exploration of underlying implicit social influence. To this end, we first employ a novel layerwise graph-enhanced variational autoencoder for the reconstruction of neighborhoods' representations, which aims to learn the pattern of social influence as well as simulate the social profile of each user for overcoming the sparsity issue in social relation data. Meanwhile, we introduce a layerwise graph attentive network for capturing the most influential scope of neighborhood. Finally, we adopt a dual sampling process to generate new social relations for enhancing the social recommendation. Extensive experiments have been conducted on three widely-used benchmark datasets, verifying the superiority of our proposed model compared with the representative approaches.
