---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Vector Lane Threading
subtitle: ''
summary: ''
authors:
- Suzanne Rivoire
- Rebecca Schultz
- Tomofumi Okuda
- admin
tags:
- Vector processors;Parallel processing;Yarn;Concurrent computing;Throughput;Hardware;Oceans;Multithreading;Bandwidth;Telecommunication
  computing
categories: []
date: '2006-08-01'
lastmod: 2022-05-15T13:35:22-07:00
featured: false
draft: false
venue: ICPP'06

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
publishDate: '2022-05-15T20:35:22.890048Z'
publication_types:
- '1'
abstract: Multi-lane vector processors achieve excellent computational throughput
  for programs with high data-level parallelism (DLP). However, application phases
  without significant DLP are unable to fully utilize the datapaths in the vector
  lanes. In this paper, we propose vector lane threading (VLT), an architectural enhancement
  that allows idle vector lanes to run short-vector or scalar threads. VLT-enhanced
  vector hardware can exploit both data-level and thread-level parallelism to achieve
  higher performance. We investigate implementation alternatives for VLT, focusing
  mostly on the instruction issue bandwidth requirements. We demonstrate that VLT's
  area overhead is small. For applications with short vectors, VLT leads to additional
  speedup of IA to 23 over the base vector design. For scalar threads, VLT outperforms
  a 2-way CMP design by a factor of two. Overall, VLT allows vector processors to
  reach high computational throughput for a wider range of parallel programs and become
  a competitive alternative to CMP systems
publication: '*Proceedings of the International Conference on Parallel Processing
  (ICPP)*'
doi: 10.1109/ICPP.2006.74
---
