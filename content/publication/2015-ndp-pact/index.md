---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Practical Near-Data Processing for In-Memory Analytics Frameworks
subtitle: ''
summary: ''
authors:
- Mingyu Gao
- Grant Ayers
- admin
tags: []
categories: []
date: '2015-09-01'
lastmod: 2022-05-15T13:35:14-07:00
featured: false
draft: false
venue: PACT'15

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
publishDate: '2022-05-15T20:35:14.423737Z'
publication_types:
- '1'
abstract: The end of Dennard scaling has made all systemsenergy-constrained. For data-intensive
  applications with limitedtemporal locality, the major energy bottleneck is data
  movementbetween processor chips and main memory modules. For such workloads, the
  best way to optimize energy is to place processing near the datain main memory.
  Advances in 3D integrationprovide an opportunity to implement near-data processing
  (NDP) withoutthe technology problems that similar efforts had in the past. This
  paper develops the hardware and software of an NDP architecturefor in-memory analytics
  frameworks, including MapReduce, graphprocessing, and deep neural networks. We develop
  simple but scalablehardware support for coherence, communication, and synchronization,
  anda runtime system that is sufficient to support analytics frameworks withcomplex
  data patterns while hiding all thedetails of the NDP hardware. Our NDP architecture
  provides up to 16x performance and energy advantageover conventional approaches,
  and 2.5x over recently-proposed NDP systems. We also investigate the balance between
  processing and memory throughput, as well as the scalability and physical and logical
  organization of the memory system. Finally, we show that it is critical to optimize
  software frameworksfor spatial locality as it leads to 2.9x efficiency improvements
  for NDP.
publication: '*Proceedings of the 2015 International Conference on Parallel Architecture
  and Compilation (PACT)*'
doi: 10.1109/PACT.2015.22
---
