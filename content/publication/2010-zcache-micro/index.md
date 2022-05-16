---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The ZCache: Decoupling Ways and Associativity'
subtitle: ''
summary: ''
authors:
- Daniel Sanchez
- admin
tags:
- multi-core
- performance
- cache
- energy efficiency
- associativity
categories: []
date: '2010-10-01'
lastmod: 2022-05-15T13:35:18-07:00
featured: false
draft: false
venue: MICRO'10

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
publishDate: '2022-05-15T20:35:18.107635Z'
publication_types:
- '1'
abstract: The ever-increasing importance of main memory latency and bandwidth is pushing
  CMPs towards caches with higher capacity and associativity. Associativity is typically
  improved by increasing the number of ways. This reduces conflict misses, but increases
  hit latency and energy, placing a stringent trade-off on cache design. We present
  the zcache, a cache design that allows much higher associativity than the number
  of physical ways (e.g. a 64-associative cache with 4 ways). The zcache draws on
  previous research on skew-associative caches and cuckoo hashing. Hits, the common
  case, require a single lookup, incurring the latency and energy costs of a cache
  with a very low number of ways. On a miss, additional tag lookups happen off the
  critical path, yielding an arbitrarily large number of replacement candidates for
  the incoming block. Unlike conventional designs, the zcache provides associativity
  by increasing the number of replacement candidates, but not the number of cache
  ways. To understand the implications of this approach, we develop a general analysis
  framework that allows to compare associativity across different cache designs (e.g.
  a set-associative cache and a zcache) by representing associativity as a probability
  distribution. We use this framework to show that for zcaches, associativity depends
  only on the number of replacement candidates, and is independent of other factors
  (such as the number of cache ways or the workload). We also show that, for the same
  number of replacement candidates, the associativity of a zcache is superior than
  that of a set-associative cache for most workloads. Finally, we perform detailed
  simulations of multithreaded and multiprogrammed workloads on a large-scale CMP
  with zcache as the last-level cache. We show that zcaches provide higher performance
  and better energy efficiency than conventional caches without incurring the overheads
  of designs with a large number of ways.
publication: '*Proceedings of the 43rd IEEE/ACM International Symposium on Microarchitecture
  (MICRO)*'
doi: 10.1109/MICRO.2010.20
---
