---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Phoenix Rebirth: Scalable MapReduce on a Large-Scale Shared-Memory System'
subtitle: ''
summary: ''
authors:
- Richard M. Yoo
- Anthony Romano
- admin
tags: []
categories: []
date: '2009-10-01'
lastmod: 2022-05-15T13:35:19-07:00
featured: false
draft: false
venue: IISWC'09

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
publishDate: '2022-05-15T20:35:19.516128Z'
publication_types:
- '1'
abstract: Dynamic runtimes can simplify parallel programming by automatically managing
  concurrency and locality without further burdening the programmer. Nevertheless,
  implementing such runtime systems for large-scale, shared-memory systems can be
  challenging. This work optimizes Phoenix, a MapReduce runtime for shared-memory
  multi-cores and multiprocessors, on a quad-chip, 32-core, 256-thread UltraSPARC
  T2+ system with NUMA characteristics. We show how a multi-layered approach that
  comprises optimizations on the algorithm, implementation, and OS interaction leads
  to significant speedup improvements with 256 threads (average of 2.5 higher speedup,
  maximum of 19 ). We also identify the roadblocks that limit the scalability of parallel
  runtimes on shared-memory systems, which are inherently tied to the OS scalability
  on large-scale systems.
publication: '*Proceedings of the 2009 IEEE International Symposium on Workload Characterization
  (IISWC)*'
doi: 10.1109/IISWC.2009.5306783
---
