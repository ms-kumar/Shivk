---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Domain Adaptation Regularization for Spectral Pruning
subtitle: ''
summary: ''
authors:
- Laurent Dillard
- Yosuke Shinya
- Taiji Suzuki
tags: []
categories: []
date: '2020-09-08'
lastmod: 2022-10-29T04:38:50Z
featured: true
draft: false

url_pdf: https://www.bmvc2020-conference.com/assets/papers/0453.pdf
links:
- name: arXiv
  url: https://arxiv.org/abs/1912.11853

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-10-29T04:38:50.716915Z'
publication_types:
- '1'
abstract: Deep Neural Networks (DNNs) have recently been achieving state-of-the-art performance on a variety of computer vision related tasks. However, their computational cost limits their ability to be implemented in embedded systems with restricted resources or strict latency constraints. Model compression has therefore been an active field of research to overcome this issue. Additionally, DNNs typically require massive amounts of labeled data to be trained. This represents a second limitation to their deployment. Domain Adaptation (DA) addresses this issue by allowing knowledge learned on one labeled source distribution to be transferred to a target distribution, possibly unlabeled. In this paper, we investigate on possible improvements of compression methods in DA setting. We focus on a compression method that was previously developed in the context of a single data distribution and show that, with a careful choice of data to use during compression and additional regularization terms directly related to DA objectives, it is possible to improve compression results. We also show that our method outperforms an existing compression method studied in the DA setting by a large margin for high compression rates. Although our work is based on one specific compression method, we also outline some general guidelines for improving compression in DA setting.
publication: '*British Machine Vision Conference (BMVC)*'
publication_info: 'Acceptance rate: 29.1%'
---
