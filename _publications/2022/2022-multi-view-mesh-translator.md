---
title: "Multi-view Human Body Mesh Translator"
date: 2022-10-04 00:00:00 +0000
selected: true
pub: "arXiv preprint"
pub_date: "2022"
cover_tag: "preprint"
cover: "/assets/images/publications/2022-multi-view-mesh-translator.jpg"
paper_tags:
  - text: "Work done while interning at MT Lab"
    variant: "info"
# abstract: >-
#   Existing methods for human mesh recovery mainly focus on single-view frameworks, but they often fail to produce accurate results due to the ill-posed setup. Considering the maturity of the multi-view motion capture system, in this paper, we propose to solve the prior ill-posed problem by leveraging multiple images from different views, thus significantly enhancing the quality of recovered meshes. In particular, we present a novel Multi-view human body Mesh Translator (MMT) model for estimating human body mesh with the help of vision transformer. Specifically, MMT takes multi-view images as input and translates them to targeted meshes in a single-forward manner. MMT fuses features of different views in both encoding and decoding phases, leading to representations embedded with global information. Additionally, to ensure the tokens are intensively focused on the human pose and shape, MMT conducts cross-view alignment at the feature level by projecting 3D keypoint positions to each view and enforcing their consistency in geometry constraints. Comprehensive experiments demonstrate that MMT outperforms existing single or multi-view models by a large margin for human mesh recovery task, notably, 28.8% improvement in MPVE over the current state-of-the-art method on the challenging HUMBI dataset. Qualitative evaluation also verifies the effectiveness of MMT in reconstructing high-quality human mesh. Codes will be made available upon acceptance.
authors:
  - Xiangjian Jiang*
  - Xuecheng Nie*
  - Zitian Wang
  - Luoqi Liu
  - Si Liu
links:
  Paper: https://arxiv.org/abs/2210.01886
---
