---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SCD: A Scalable Coherence Directory with Flexible Sharer Set Encoding'
subtitle: ''
summary: ''
authors:
- Daniel Sanchez
- admin
tags: []
categories: []
date: '2012-02-01'
lastmod: 2022-05-15T13:35:17-07:00
featured: false
draft: false
venue: HPCA'12

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
publishDate: '2022-05-15T20:35:17.122366Z'
publication_types:
- '1'
abstract: "Large-scale CMPs with hundreds of cores require a directory-based protocol\
  \ to maintain cache coherence. However, previously proposed coherence directories\
  \ are hard to scale beyond tens of cores, requiring either excessive area or energy,\
  \ complex hierarchical protocols, or inexact representations of sharer sets that\
  \ increase coherence traffic and degrade performance. We present SCD, a scalable\
  \ coherence directory that relies on efficient highly-associative caches (such as\
  \ zcaches) to implement a single-level directory that scales to thousands of cores,\
  \ tracks sharer sets exactly, and incurs negligible directory-induced invalidations.\
  \ SCD scales because, unlike conventional directories, it uses a variable number\
  \ of directory tags to represent sharer sets: lines with one or few sharers use\
  \ a single tag, while widely shared lines use additional tags, so tags remain small\
  \ as the system scales up. We show that, thanks to the efficient highly-associative\
  \ array it relies on, SCD can be fully characterized using analytical models, and\
  \ can be sized to guarantee a negligible number of evictions independently of the\
  \ workload. We evaluate SCD using simulations of a 1024-core CMP. For the same level\
  \ of coverage, we find that SCD is 13 more area-efficient than full-map sparse directories,\
  \ and 2 more area-efficient and faster than hierarchical directories, while requiring\
  \ a simpler protocol. Furthermore, we show that SCD's analytical models are accurate\
  \ in practice."
publication: '*Proceedings of the 2012 IEEE 18th International Symposium on High-Performance
  Computer Architecture (HPCA)*'
doi: 10.1109/HPCA.2012.6168950
---
