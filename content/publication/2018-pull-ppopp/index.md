---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Making Pull-Based Graph Processing Performant
subtitle: ''
summary: ''
authors:
- Samuel Grossman
- Heiner Litz
- admin
tags: []
categories: []
date: '2018-02-01'
lastmod: 2022-05-15T13:35:12-07:00
featured: false
draft: false
venue: PPoPP'18

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
publishDate: '2022-05-15T20:35:12.618760Z'
publication_types:
- '1'
abstract: Graph processing engines following either the push-based or pull-based pattern
  conceptually consist of a two-level nested loop structure. Parallelizing and vectorizing
  these loops is critical for high overall performance and memory bandwidth utilization.
  Outer loop parallelization is simple for both engine types but suffers from high
  load imbalance. This work focuses on inner loop parallelization for pull engines,
  which when performed naively leads to a significant increase in conflicting memory
  writes that must be synchronized.Our first contribution is a scheduler-aware interface
  for parallel loops that allows us to optimize for the common case in which each
  thread executes several consecutive iterations. This eliminates most write traffic
  and avoids all synchronization, leading to speedups of up to 50X.Our second contribution
  is the Vector-Sparse format, which addresses the obstacles to vectorization that
  stem from the commonly-used Compressed-Sparse data structure. Our new format eliminates
  unaligned memory accesses and bounds checks within vector operations, two common
  problems when processing low-degree vertices. Vectorization with Vector-Sparse leads
  to speedups of up to 2.5X.Our contributions are embodied in Grazelle, a hybrid graph
  processing framework. On a server equipped with four Intel Xeon E7-4850 v3 processors,
  Grazelle respectively outperforms Ligra, Polymer, GraphMat, and X-Stream by up to
  15.2X, 4.6X, 4.7X, and 66.8X.
publication: '*Proceedings of the 23rd ACM SIGPLAN Symposium on Principles and Practice
  of Parallel Programming (PPoPP)*'
doi: 10.1145/3178487.3178506
---
