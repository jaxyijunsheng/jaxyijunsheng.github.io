---
title: "Dual space multi-granular model for multi-interest sequential recommendation"
collection: publications
category: manuscripts
permalink: /publication/DSMGRec
excerpt: 'This paper is my first work.'
date: 2025-7-01
venue: 'Knowledge-Based Systems'
slidesurl: #'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S095070512500810X'
bibtexurl: #'https://www.sciencedirect.com/sdfe/arp/cite?pii=S095070512500810X&format=text%2Fx-bibtex&withabstract=true'
citation: '<strong>Sheng, Y.</strong>, Lei, P., Liu, Y., Chen, X., Xu, Q., & Gong, Z. (2025). "Dual space multi-granular model for multi-interest sequential recommendation." <i>Knowledge-Based Systems</i>.'
#Sheng, Y., Lei, P., Liu, Y., Chen, X., Xu, Q., & Gong, Z. (2025). "Dual space multi-granular model for multi-interest sequential recommendation." <i>Knowledge-Based Systems</i>.

#Chen, X., Lei, P. I., Sheng, Y., Liu, Y., & Gong, Z. (2024, October). "Social influence learning for recommendation systems." In <i>Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM)</i>, pp. 312–322.

#Liu, Y., Lei, P., Sheng, Y., Chen, X., & Gong, Z. (2025). "Efficient energy-based neural topic modeling with embeddings." <i>Neurocomputing</i>, 638, 130179.

---
***Abstract***
Sequential recommendation aims to predict the next item for a user given his historical interaction sequence. Recently, multi-interest and Graph Neural Network (GNN) based paradigms are two new directions in such task. Multi-interest learning encompasses extracting diverse user interests through historical item clustering, while GNN refines user preferences through correlations among historical items. Recent research suggests the synergistic potential of combining these methods to aggregate user preferences at multiple levels, enhancing the accuracy of multi-interest extraction for improved recommendations. However, existing GNN-based multi-interest models can only achieve local smoothing for node embeddings through neighbor information aggregating, thus, they could not match remote items (far-apart items on the item–item graph) even though those remote items show similar local patterns and the items may reflect some niche preferences. It is unreasonable in the context of multi-interest recommendation as the objective is to capture the user’s interests in a more comprehensive manner. To tackle this issue, we propose a Dual Space Multi-Granular Recommendation model (DSMGRec), where a Graph Deconvolutional Network (GDcN) is designed to disentangle local structure-based patterns of items as their additional embeddings. Then, we adopt a dual framework that combines the traditional GNN with our novel GDcN to encode multi-granular representations for items in the dual space. Such dual item representations can match items by not only their primary patterns but also their secondary patterns. Experiments on four real-world datasets with different densities show that our model outperforms state-of-the-art baselines.
