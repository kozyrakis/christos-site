---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning Memory Access Patterns
subtitle: ''
summary: ''
authors:
- Milad Hashemi
- Kevin Swersky
- Jamie Smith
- Grant Ayers
- Heiner Litz
- Jichuan Chang
- admin
- Parthasarathy Ranganathan
tags: []
categories: []
date: '2018-07-01'
lastmod: 2022-05-15T13:35:11-07:00
featured: false
draft: false
venue: ICML'18

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
publishDate: '2022-05-15T20:35:11.635135Z'
publication_types:
- '1'
abstract: The explosion in workload complexity and the recent slow-down in Moore’s
  law scaling call for new approaches towards efficient computing. Researchers are
  now beginning to use recent advances in machine learning in software optimizations;
  augmenting or replacing traditional heuristics and data structures. However, the
  space of machine learning for computer hardware architecture is only lightly explored.
  In this paper, we demonstrate the potential of deep learning to address the von
  Neumann bottleneck of memory performance. We focus on the critical problem of learning
  memory access patterns, with the goal of constructing accurate and efficient memory
  prefetchers. We relate contemporary prefetching strategies to n-gram models in natural
  language processing, and show how recurrent neural networks can serve as a drop-in
  replacement. On a suite of challenging benchmark datasets, we find that neural networks
  consistently demonstrate superior performance in terms of precision and recall.
  This work represents the first step towards practical neural-network based prefetching,
  and opens a wide range of exciting directions for machine learning in computer architecture
  research.
publication: '*Proceedings of the 35th International Conference on Machine Learning  (ICML)*'
links:
- name: URL
  url: https://proceedings.mlr.press/v80/hashemi18a.html
---
