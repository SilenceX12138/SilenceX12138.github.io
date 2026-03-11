---
title: "TabEBM: A Tabular Data Augmentation Method with Distinct Class-Specific Energy-Based Models"
date: 2024-09-25 00:00:00 +0000
selected: true
pub: "The Thirty-Eighth Annual Conference on Neural Information Processing Systems"
pub_date: "2024"
cover_tag: "NeurIPS"
cover: "/assets/images/publications/2024-tabebm-neurips.jpg"
# citation_count: 0
# paper_tags:
#   - text: "Oral (Top 1.18%)"
#     variant: "info"
# abstract: >-
#   Data collection is often difficult in critical fields such as medicine, physics, and chemistry. As a result, classification methods usually perform poorly with these small datasets, leading to weak predictive performance. Increasing the training set with additional synthetic data, similar to data augmentation in images, is commonly believed to improve downstream classification performance. However, current tabular generative methods that learn either the joint distribution p(x,y) or the class-conditional distribution p(x|y) often overfit on small datasets, resulting in poor-quality synthetic data, usually worsening classification performance compared to using real data alone. To solve these challenges, we introduce TabEBM, a novel class-conditional generative method using Energy-Based Models (EBMs). Unlike existing methods that use a shared model to approximate all class-conditional densities, our key innovation is to create distinct EBM generative models for each class, each modelling its class-specific data distribution individually. This approach creates robust energy landscapes, even in ambiguous class distributions. Our experiments show that TabEBM generates synthetic data with higher quality and better statistical fidelity than existing methods. When used for data augmentation, our synthetic data consistently improves the classification performance across diverse datasets of various sizes, especially small ones.
authors:
  - Andrei Margeloiu*
  - Xiangjian Jiang*
  - Nikola Simidjievski
  - Mateja Jamnik
links:
  Paper: https://arxiv.org/abs/2409.16118
  Code: https://github.com/andreimargeloiu/TabEBM
  Poster: https://neurips.cc/media/PosterPDFs/NeurIPS%202024/103143.png?t=1731278908.4883428
  Project: https://github.com/andreimargeloiu/TabEBM
  Slides: https://nips.cc/media/neurips-2024/Slides/95948.pdf
  Video: https://nips.cc/virtual/2024/poster/95948
---
