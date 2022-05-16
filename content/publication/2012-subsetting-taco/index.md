---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Improving System Energy Efficiency with Memory Rank Subsetting
subtitle: ''
summary: ''
authors:
- Jung Ho Ahn
- Norman P. Jouppi
- admin
- Jacob Leverich
- Robert S. Schreiber
tags:
- overfetch
- rank subsetting
- Memory system
- mini-rank
- DRAM
- multicore DIMM
categories: []
date: '2012-03-01'
lastmod: 2022-05-15T13:35:17-07:00
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
publishDate: '2022-05-15T20:35:17.042068Z'
publication_types:
- '2'
abstract: VLSI process technology scaling has enabled dramatic improvements in the
  capacity and peak bandwidth of DRAM devices. However, current standard DDRx DIMM
  memory interfaces are not well tailored to achieve high energy efficiency and performance
  in modern chip-multiprocessor-based computer systems. Their suboptimal performance
  and energy inefficiency can have a significant impact on system-wide efficiency
  since much of the system power dissipation is due to memory power. New memory interfaces,
  better suited for future many-core systems, are needed. In response, there are recent
  proposals to enhance the energy efficiency of main-memory systems by dividing a
  memory rank into subsets, and making a subset rather than a whole rank serve a memory
  request.We holistically assess the effectiveness of rank subsetting from system-wide
  performance, energy-efficiency, and reliability perspectives. We identify the impact
  of rank subsetting on memory power and processor performance analytically, compare
  two promising rank-subsetting proposals, Multicore DIMM and mini-rank, and verify
  our analysis by simulating a chip-multiprocessor system using multithreaded and
  consolidated workloads. We extend the design of Multicore DIMM for high-reliability
  systems and show that compared with conventional chipkill approaches, rank subsetting
  can lead to much higher system-level energy efficiency and performance at the cost
  of additional DRAM devices. This holistic assessment shows that rank subsetting
  offers compelling alternatives to existing processor-memory interfaces for future
  DDR systems.
publication: '*ACM Transactions on Architecture and Code Optimization*'
doi: 10.1145/2133382.2133386
---
