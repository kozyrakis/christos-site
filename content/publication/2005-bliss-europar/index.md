---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Improving Instruction Delivery with a Block-Aware ISA
subtitle: ''
summary: ''
authors:
- Ahmad Zmily
- Earl Killian
- admin
tags: []
categories: []
date: '2005-08-01'
lastmod: 2022-05-15T13:35:24-07:00
featured: false
draft: false
venue: EuroPar'05

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
publishDate: '2022-05-15T20:35:24.117133Z'
publication_types:
- '1'
abstract: Instruction delivery is a critical component for wide-issue processors since
  its bandwidth and accuracy place an upper limit on performance. The processor front-end
  accuracy and bandwidth are limited by instruction cache misses, multi-cycle instruction
  cache accesses, and target or direction mispredictions for control-flow operations.
  This paper introduces a block-aware ISA (BLISS) that helps accurate instruction
  delivery by defining basic block descriptors in addition to and separate from the
  actual instructions in a program. We show that BLISS allows for a decoupled front-end
  that tolerates cache latency and allows for higher speculation accuracy. This translates
  to a 20% IPC and 14% energy improvements over conventional front-ends. We also demonstrate
  that a BLISS-based front-end outperforms by 13% decoupled front-ends that detect
  fetched blocks dynamically in hardware, without any information from the ISA.
publication: '*Proceedings of the 11th International Euro-Par Conference on Parallel
  Processing (Euro-Par)*'
doi: 10.1007/11549468_60
---
