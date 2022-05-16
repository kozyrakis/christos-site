---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Analysis of On-Chip Interconnection Networks for Large-Scale Chip Multiprocessors
subtitle: ''
summary: ''
authors:
- Daniel Sanchez
- George Michelogiannakis
- admin
tags:
- Networks-on-chip
- hierarchical networks
- chip multiprocessors
categories: []
date: '2010-05-01'
lastmod: 2022-05-15T13:35:18-07:00
featured: false
draft: false
venue: ACM TACO

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
publishDate: '2022-05-15T20:35:18.597542Z'
publication_types:
- '2'
abstract: With the number of cores of chip multiprocessors (CMPs) rapidly growing
  as technology scales down, connecting the different components of a CMP in a scalable
  and efficient way becomes increasingly challenging. In this article, we explore
  the architectural-level implications of interconnection network design for CMPs
  with up to 128 fine-grain multithreaded cores. We evaluate and compare different
  network topologies using accurate simulation of the full chip, including the memory
  hierarchy and interconnect, and using a diverse set of scientific and engineering
  workloads.We find that the interconnect has a large impact on performance, as it
  is responsible for 60% to 75% of the miss latency. Latency, and not bandwidth, is
  the primary performance constraint, since, even with many threads per core and workloads
  with high miss rates, networks with enough bandwidth can be efficiently implemented
  for the system scales we consider. From the topologies we study, the flattened butterfly
  consistently outperforms the mesh and fat tree on all workloads, leading to performance
  advantages of up to 22%. We also show that considering interconnect and memory hierarchy
  together when designing large-scale CMPs is crucial, and neglecting either of the
  two can lead to incorrect conclusions. Finally, the effect of the interconnect on
  overall performance becomes more important as the number of cores increases, making
  interconnection choices especially critical when scaling up.
publication: '*ACM Transactions on Architure and Code Optimization*'
doi: 10.1145/1736065.1736069
---
