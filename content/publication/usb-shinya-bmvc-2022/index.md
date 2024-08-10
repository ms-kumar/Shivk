---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'USB: Universal-Scale Object Detection Benchmark'
subtitle: ''
summary: ''
authors:
- Yosuke Shinya
tags: []
categories: []
date: '2022-11-21'
lastmod: 2022-10-29T04:38:50Z
featured: true
draft: false

url_pdf: https://bmvc2022.mpi-inf.mpg.de/0261.pdf
links:
- name: arXiv
  url: https://arxiv.org/abs/2103.14027
- name: Code
  url: https://github.com/shinya7y/UniverseNet
- name: Slides
  url: https://github.com/shinya7y/shinya7y.github.io/releases/download/v5.7.1/usb-shinya-bmvc-2022-slides.pdf
- name: Poster
  url: https://bmvc2022.mpi-inf.mpg.de/0261_poster.pdf

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
publishDate: '2022-10-29T04:38:38.761521Z'
publication_types:
- '1'
abstract: Benchmarks, such as COCO, play a crucial role in object detection. However, existing benchmarks are insufficient in scale variation, and their protocols are inadequate for fair comparison. In this paper, we introduce the Universal-Scale object detection Benchmark (USB). USB has variations in object scales and image domains by incorporating COCO with the recently proposed Waymo Open Dataset and Manga109-s dataset. To enable fair comparison and inclusive research, we propose training and evaluation protocols. They have multiple divisions for training epochs and evaluation image resolutions, like weight classes in sports, and compatibility across training protocols, like the backward compatibility of the Universal Serial Bus. Specifically, we request participants to report results with not only higher protocols (longer training) but also lower protocols (shorter training). Using the proposed benchmark and protocols, we conducted extensive experiments using 15 methods and found weaknesses of existing COCO-biased methods.
publication: '*British Machine Vision Conference (BMVC)*'
---
