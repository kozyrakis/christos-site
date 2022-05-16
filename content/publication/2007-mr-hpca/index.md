---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Evaluating MapReduce for Multi-Core and Multiprocessor Systems
subtitle: ''
summary: ''
authors:
- Colby Ranger
- Ramanan Raghuraman
- Arun Penmetsa
- Gary Bradski
- admin
tags: []
categories: []
date: '2007-02-01'
lastmod: 2022-05-15T13:35:22-07:00
featured: false
draft: false
venue: HPCA'07

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
publishDate: '2022-05-15T20:35:22.065730Z'
publication_types:
- '1'
abstract: This paper evaluates the suitability of the MapReduce model for multi-core
  and multi-processor systems. MapReduce was created by Google for application development
  on data-centers with thousands of servers. It allows programmers to write functional-style
  code that is automaticatlly parallelized and scheduled in a distributed system.
  We describe Phoenix, an implementation of MapReduce for shared-memory systems that
  includes a programming API and an efficient runtime system. The Phoenix run-time
  automatically manages thread creation, dynamic task scheduling, data partitioning,
  and fault tolerance across processor nodes. We study Phoenix with multi-core and
  symmetric multiprocessor systems and evaluate its performance potential and error
  recovery features. We also compare MapReduce code to code written in lower-level
  APIs such as P-threads. Overall, we establish that, given a careful implementation,
  MapReduce is a promising model for scalable performance on shared-memory systems
  with simple parallel code.
publication: '*Proceedings of the IEEE 13th International Symposium on High Performance
  Computer Architecture (HPCA)*'
doi: 10.1109/HPCA.2007.346181
---
