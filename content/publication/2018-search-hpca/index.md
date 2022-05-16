---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Memory Hierarchy for Web Search
subtitle: ''
summary: ''
authors:
- Grant Ayers
- Jung Ho Ahn
- admin
- Parthasarathy Ranganathan
tags:
- Production;Servers;Indexes;Microarchitecture;Web search;Benchmark testing;Hardware;web
  search;warehouse scale computing;memory systems
categories: []
date: '2018-02-01'
lastmod: 2022-05-15T13:35:12-07:00
featured: false
draft: false
venue: HPCA'18

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
publishDate: '2022-05-15T20:35:12.536512Z'
publication_types:
- '1'
abstract: Online data-intensive services, such as search, serve billions of users,
  utilize millions of cores, and comprise a significant and growing portion of datacenter-scale
  workloads. However, the complexity of these workloads and their proprietary nature
  has precluded detailed architectural evaluations and optimizations of processor
  design trade-offs. We present the first detailed study of the memory hierarchy for
  the largest commercial search engine today. We use a combination of measurements
  from longitudinal studies across tens of thousands of deployed servers, systematic
  microarchitectural evaluation on individual platforms, validated trace-driven simulation,
  and performance modeling – all driven by production workloads servicing real-world
  user requests. Our data quantifies significant differences between production search
  and benchmarks commonly used in the architecture community. We identify the memory
  hierarchy as an important opportunity for performance optimization, and present
  new insights pertaining to how search stresses the cache hierarchy, both for instructions
  and data. We show that, contrary to conventional wisdom, there is significant reuse
  of data that is not captured by current cache hierarchies, and discuss why this
  precludes state-of-the-art tiled and scale-out architectures. Based on these insights,
  we rethink a new cache hierarchy optimized for search that trades off the inefficient
  use of L3 cache transistors for higher-performance cores, and adds a latency-optimized
  on-package eDRAM L4 cache. Compared to state-of-the-art processors, our proposed
  design performs 27% to 38% better.
publication: '*2018 IEEE International Symposium on High Performance Computer Architecture
  (HPCA)*'
doi: 10.1109/HPCA.2018.00061
---
