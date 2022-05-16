---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'MARS: Adaptive Remote Execution for Multi-Threaded Mobile Devices'
subtitle: ''
summary: ''
authors:
- Asaf Cidon
- Tomer M. London
- Sachin Katti
- admin
- Mendel Rosenblum
tags: []
categories: []
date: '2011-10-01'
lastmod: 2022-05-15T13:35:17-07:00
featured: false
draft: false
venue: MobiHeld'11

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
publishDate: '2022-05-15T20:35:17.286755Z'
publication_types:
- '1'
abstract: Mobile devices face a growing demand to support computationally intensive
  applications like 3D graphics and computer vision. However, these devices are inherently
  limited by processor power density and device battery life. Dynamic remote execution
  addresses this problem, by enabling mobile devices to opportunistically offload
  computations to a remote server. We envision remote execution as a new type of cloud-based
  heterogeneous computing resource, or a \"Cloud-on-Chip\", which would be managed
  as a system resource as if it were a local CPU, with a highly variable wireless
  interconnect. To realize this vision, we introduce MARS, the first adaptive, online
  and lightweight RPC-based remote execution scheduler supporting multi-threaded and
  multi-core systems. MARS uses a novel efficient offloading decision algorithm that
  takes into account the inherent trade-offs between communication and computation
  delays and power consumption. Due to its lightweight design, MARS runs on the device
  itself, instantly adapts its decisions to changing wireless resources, and supports
  any number of threads and cores. We evaluated MARS using a trace-based simulator
  driven by real world measurements on augmented reality, face recognition and video
  game applications. MARS achieves an average speedup of 57% and 33% higher energy
  savings over the best static client-server partitions.
publication: '*Proceedings of the 3rd ACM SOSP Workshop on Networking, Systems, and
  Applications on Mobile Handhelds (MobiHeld)*'
doi: 10.1145/2043106.2043107
---
