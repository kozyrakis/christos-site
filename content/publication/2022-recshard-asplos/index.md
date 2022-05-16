---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'RecShard: Statistical Feature-Based Memory Optimization for Industry-Scale
  Neural Recommendation'
subtitle: ''
summary: ''
authors:
- Geet Sethi
- Bilge Acun
- Niket Agarwal
- admin
- Caroline Trippel
- Carole-Jean Wu
tags:
- AI training systems
- Neural networks
- Memory optimization
- Deep learning recommendation models
categories: []
date: '2022-03-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue: ASPLOS'22

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
publishDate: '2022-05-15T20:35:09.117156Z'
publication_types:
- '1'
abstract: We propose RecShard, a fine-grained embedding table (EMB) partitioning and
  placement technique for deep learning recommendation models (DLRMs). RecShard is
  designed based on two key observations. First, not all EMBs are equal, nor all rows
  within an EMB are equal in terms of access patterns. EMBs exhibit distinct memory
  characteristics, providing performance optimization opportunities for intelligent
  EMB partitioning and placement across a tiered memory hierarchy. Second, in modern
  DLRMs, EMBs function as hash tables. As a result, EMBs display interesting phenomena,
  such as the birthday paradox, leaving EMBs severely under-utilized. RecShard determines
  an optimal EMB sharding strategy for a set of EMBs based on training data distributions
  and model characteristics, along with the bandwidth characteristics of the underlying
  tiered memory hierarchy. In doing so, RecShard achieves over 6 times higher EMB
  training throughput on average for capacity constrained DLRMs. The throughput increase
  comes from improved EMB load balance by over 12 times and from the reduced access
  to the slower memory by over 87 times.
publication: '*Proceedings of the 27th ACM International Conference on Architectural
  Support for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/3503222.3507777
---
