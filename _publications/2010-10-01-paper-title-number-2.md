---
title: "Efficient energy-based neural topic modeling with embeddings."
collection: publications
category: manuscripts
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'This paper is done by my senior colleague Yanyan.'
date: 2025-7-1
venue: 'Neurocomputing'
slidesurl: #'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0925231225008513'
citation: 'Liu Yanyan, Lei Pui Ieng, <strong>Sheng Yijun</strong>, Chen Ximing, & Gong Zhiguo*. (2025). Efficient energy-based neural topic modeling with embeddings. <i>Neurocomputing</i>, 638, 130179.'
---
***Abstract***

Recently, topic models based on deep neural networks have garnered significant attention due to their robust ability to capture latent topic structures. However, existing neural topic models face challenges such as approximate posterior inference errors or the computational intensity of iterative transport distance calculations. Additionally, a common limitation of these models is their dependence on pre-defined priors to constrain latent topic structures. This reliance can limit the expressive capacity of topic variables and reduce topic heterogeneity across diverse corpora. To address these issues, we propose an efficient embedding-derived topic model framework that captures the interrelations among documents, topics, and words through embedding agreements, enabling faster training. Furthermore, we introduce a learnable topic prior constraint for latent topic structures, formulated through an energy function, and design an effective joint optimization for both embeddings and the learnable topic prior. Extensive experiments on six widely-used datasets demonstrate that our approach outperforms existing state-of-the-art topic models.
