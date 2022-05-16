---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'AsmDB: Understanding and Mitigating Front-End Stalls in Warehouse-Scale Computers'
subtitle: ''
summary: ''
authors:
- Grant Ayers
- Nayana Prasad Nagendra
- David I. August
- Hyoun Kyu Cho
- Svilen Kanev
- admin
- Trivikram Krishnamurthy
- Heiner Litz
- Tipp Moseley
- Parthasarathy Ranganathan
tags: []
categories: []
date: '2019-06-01'
lastmod: 2022-05-15T13:35:11-07:00
featured: false
draft: false
venue: ISCA'19 

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
publishDate: '2022-05-15T20:35:11.311686Z'
publication_types:
- '1'
abstract: 'The large instruction working sets of private and public cloud workloads
  lead to frequent instruction cache misses and costs in the millions of dollars.
  While prior work has identified the growing importance of this problem, to date,
  there has been little analysis of where the misses come from, and what the opportunities
  are to improve them. To address this challenge, this paper makes three contributions.
  First, we present the design and deployment of a new, always-on, fleet-wide monitoring
  system, AsmDB, that tracks front-end bottlenecks. AsmDB uses hardware support to
  collect bursty execution traces, fleet-wide temporal and spatial sampling, and sophisticated
  offline post-processing to construct full-program dynamic control-flow graphs. Second,
  based on a longitudinal analysis of AsmDB data from real-world online services,
  we present two detailed insights on the sources of front-end stalls: (1) cold code
  that is brought in along with hot code leads to significant cache fragmentation
  and a corresponding large number of instruction cache misses; (2) distant branches
  and calls that are not amenable to traditional cache locality or next-line prefetching
  strategies account for a large fraction of cache misses. Third, we prototype two
  optimizations that target these insights. For misses caused by fragmentation, we
  focus on memcmp, one of the hottest functions contributing to cache misses, and
  show how fine-grained layout optimizations lead to significant benefits. For misses
  at the targets of distant jumps, we propose new hardware support for software code
  prefetching and prototype a new feedback-directed compiler optimization that combines
  static program flow analysis with dynamic miss profiles to demonstrate significant
  benefits for several large warehouse-scale workloads. Improving upon prior work,
  our proposal avoids invasive hardware modifications by prefetching via software
  in an efficient and scalable way. Simulation results show that such an approach
  can eliminate up to 96% of instruction cache misses with negligible overheads.'
publication: '*Proceedings of the 46th International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/3307650.3322234
---
