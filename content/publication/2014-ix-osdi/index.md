---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'IX: A Protected Dataplane Operating System for High Throughput and Low Latency'
subtitle: ''
summary: ''
authors:
- Adam Belay
- George Prekas
- Ana Klimovic
- Samuel Grossman
- admin
- Edouard Bugnion
tags: []
categories: []
date: '2014-10-01'
lastmod: 2022-05-15T13:35:15-07:00
featured: false
draft: false
venue: OSDI'14

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
publishDate: '2022-05-15T20:35:15.156334Z'
publication_types:
- '1'
abstract: The conventional wisdom is that aggressive networking requirements, such
  as high packet rates for small messages and microsecond-scale tail latency, are
  best addressed outside the kernel, in a user-level networking stack. We present
  IX, a dataplane operating system that provides high I/O performance, while maintaining
  the key advantage of strong protection offered by existing kernels. IX uses hardware
  virtualization to separate management and scheduling functions of the kernel (control
  plane) from network processing (dataplane). The data-plane architecture builds upon
  a native, zero-copy API and optimizes for both bandwidth and latency by dedicating
  hardware threads and networking queues to data-plane instances, processing bounded
  batches of packets to completion, and by eliminating coherence traffic and multi-core
  synchronization. We demonstrate that IX outperforms Linux and state-of-the-art,
  user-space network stacks significantly in both throughput and end-to-end latency.
  Moreover, IX improves the throughput of a widely deployed, key-value store by up
  to 3.6x and reduces tail latency by more than 2x.
publication: '*Proceedings of the 11th USENIX Conference on Operating Systems Design
  and Implementation (OSDI)*'
---
