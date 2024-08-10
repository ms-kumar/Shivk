---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Contrastive Relevance Propagation for Interpreting Predictions by a Single-Shot
  Object Detector
subtitle: ''
summary: ''
authors:
- Hideomi Tsunakawa
- Yoshitaka Kameya
- Hanju Lee
- Yosuke Shinya
- Naoki Mitsumoto
tags: []
categories: []
date: '2019-07-18'
lastmod: 2022-10-29T04:38:51Z
featured: true
draft: false

url_pdf: https://www.researchgate.net/profile/Yoshitaka-Kameya/publication/332344761_Contrastive_Relevance_Propagation_for_Interpreting_Predictions_by_a_Single-Shot_Object_Detector/links/5db39aa1a6fdccc99d9d085b/Contrastive-Relevance-Propagation-for-Interpreting-Predictions-by-a-Single-Shot-Object-Detector.pdf
links:
- name: Slides
  url: https://rjida.meijo-u.ac.jp/kameya/publication/Tsunakawa-IJCNN19-slides.pdf
- name: IEEE
  url: https://ieeexplore.ieee.org/document/8851770

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
publishDate: '2022-10-29T04:38:51.002997Z'
publication_types:
- '1'
abstract: Object detection is a widely-used computer vision task, in which we identify a bounding box around each object in an image and classify the object into one of pre-defined classes. Single Shot MultiBox Detector (SSD) is a real-time object detector based on a single convolutional neural network. SSD is popular and known for high speed and accuracy, but its black-box nature is not ignorable when it is applied to critical systems. In this paper, we propose Contrastive Relevance Propagation (CRP), an extension of Layer-wise Relevance Propagation (LRP) tailored for SSD. CRP can consistently deal with SSD's heterogeneous output, i.e. confidences for object classes and location offsets, and create a heatmap that highlights a crucial part of the input, which is not available with a standard use of LRP. By experiments with the Pascal VOC 2012 dataset, we confirmed the quality of heatmaps created by CRP, and with such heatmaps, we conducted a simple analysis on prediction errors made by SSD.
publication: '*International Joint Conference on Neural Networks (IJCNN)*'
publication_info: 'Oral presentation, Acceptance rate: 36.4%'
---
