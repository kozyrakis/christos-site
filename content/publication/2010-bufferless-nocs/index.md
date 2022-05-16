---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Evaluating Bufferless Flow Control for On-Chip Networks
subtitle: ''
summary: ''
authors:
- George Michelogiannakis
- Daniel Sanchez
- William J. Dally
- admin
tags:
- Networks
- Multiprocessor interconnection
- Flow control
- Buffers
categories: []
date: '2010-05-01'
lastmod: 2022-05-15T13:35:18-07:00
featured: false
draft: false
venue: NOCS'10 

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
publishDate: '2022-05-15T20:35:18.681117Z'
publication_types:
- '1'
abstract: 'With the emergence of on-chip networks, the power consumed by router buffers
  has become a primary concern. Bufferless flow control addresses this issue by removing
  router buffers, and handles contention by dropping or deflecting flits. This work
  compares virtual-channel (buffered) and deflection (packet-switched bufferless)
  flow control. Our evaluation includes optimizations for both schemes: buffered networks
  use custom SRAM-based buffers and empty buffer bypassing for energy efficiency,
  while bufferless networks feature a novel routing scheme that reduces average latency
  by 5%. Results show that unless process constraints lead to excessively costly buffers,
  the performance, cost and increased complexity of deflection flow control outweigh
  its potential gains: bufferless designs are only marginally (up to 1.5%) more energy
  efficient at very light loads, and buffered networks provide lower latency and higher
  throughput per unit power under most conditions.'
publication: '*Proceedings of the 4th ACM/IEEE International Symposium on Networks-on-Chip
  (NOCS)*'
doi: 10.1109/NOCS.2010.10
---
