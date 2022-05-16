---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Vantage: Scalable and Efficient Fine-Grain Cache Partitioning'
subtitle: ''
summary: ''
authors:
- Daniel Sanchez
- admin
tags:
- qos
- shared cache
- multi-core
- cache partitioning
categories: []
date: '2011-06-01'
lastmod: 2022-05-15T13:35:17-07:00
featured: false
draft: false
venue: ISCA'11

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
publishDate: '2022-05-15T20:35:17.861727Z'
publication_types:
- '1'
abstract: 'Cache partitioning has a wide range of uses in CMPs, from guaranteeing
  quality of service and controlled sharing to security-related techniques. However,
  existing cache partitioning schemes (such as way-partitioning) are limited to coarse-grain
  allocations, can only support few partitions, and reduce cache associativity, hurting
  performance. Hence, these techniques can only be applied to CMPs with 2-4 cores,
  but fail to scale to tens of cores.We present Vantage, a novel cache partitioning
  technique that overcomes the limitations of existing schemes: caches can have tens
  of partitions with sizes specified at cache line granularity, while maintaining
  high associativity and strong isolation among partitions. Vantage leverages cache
  arrays with good hashing and associativity, which enable soft-pinning a large portion
  of cache lines. It enforces capacity allocations by controlling the replacement
  process. Unlike prior schemes, Vantage provides strict isolation guarantees by partitioning
  most (e.g. 90%) of the cache instead of all of it. Vantage is derived from analytical
  models, which allow us to provide strong guarantees and bounds on associativity
  and sizing independent of the number of partitions and their behaviors. It is simple
  to implement, requiring around 1.5% state overhead and simple changes to the cache
  controller.We evaluate Vantage using extensive simulations. On a 32-core system,
  using 350 multiprogrammed workloads and one partition per core, partitioning the
  last-level cache with conventional techniques degrades throughput for 71% of the
  workloads versus an unpartitioned cache (by 7% average, 25% maximum degradation),
  even when using 64-way caches. In contrast, Vantage improves throughput for 98%
  of the workloads, by 8% on average (up to 20%), using a 4-way cache.'
publication: '*Proceedings of the 38th  International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/2000064.2000073
---
