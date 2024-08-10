---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Understanding the Effects of Pre-Training for Object Detectors via Eigenspectrum
subtitle: ''
summary: ''
authors:
- Yosuke Shinya
- Edgar Simo-Serra
- Taiji Suzuki
tags: []
categories: []
date: '2019-10-28'
lastmod: 2022-10-29T04:38:50Z
featured: true
draft: false

url_pdf: https://esslab.jp/~ess/publications/ShinyaICCVW2019.pdf
links:
- name: arXiv
  url: https://arxiv.org/abs/1909.04021
- name: Slides
  url: https://neuralarchitects.org/slides/shinya-slides.pdf
- name: IEEE
  url: https://ieeexplore.ieee.org/document/9022267
- name: CVF
  url: https://openaccess.thecvf.com/content_ICCVW_2019/html/NeurArch/Shinya_Understanding_the_Effects_of_Pre-Training_for_Object_Detectors_via_Eigenspectrum_ICCVW_2019_paper.html

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
publishDate: '2022-10-29T04:38:50.861161Z'
publication_types:
- '1'
abstract: ImageNet pre-training has been regarded as essential for training accurate object detectors for a long time. Recently, it has been shown that object detectors trained from randomly initialized weights can be on par with those fine-tuned from ImageNet pre-trained models. However, the effects of pre-training and the differences caused by pre-training are still not fully understood. In this paper, we analyze the eigenspectrum dynamics of the covariance matrix of each feature map in object detectors. Based on our analysis on ResNet-50, Faster R-CNN with FPN, and Mask R-CNN, we show that object detectors trained from ImageNet pre-trained models and those trained from scratch behave differently from each other even if both object detectors have similar accuracy. Furthermore, we propose a method for automatically determining the widths (the numbers of channels) of object detectors based on the eigenspectrum. We train Faster R-CNN with FPN from randomly initialized weights, and show that our method can reduce ~27% of the parameters of ResNet-50 without increasing Multiply-Accumulate operations and losing accuracy. Our results indicate that we should develop more appropriate methods for transferring knowledge from image classification to object detection (or other tasks).
publication: '*International Conference on Computer Vision Workshops (ICCVW)*'
publication_info: 'Oral presentation, Acceptance rate: 9%, Best Paper Award Nominee'
---
