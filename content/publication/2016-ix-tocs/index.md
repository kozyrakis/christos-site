---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The IX Operating System: Combining Low Latency, High Throughput, and Efficiency
  in a Protected Dataplane'
subtitle: ''
summary: ''
authors:
- Adam Belay
- George Prekas
- Mia Primorac
- Ana Klimovic
- Samuel Grossman
- admin
- Edouard Bugnion
tags:
- Virtualization
- latency-critical applications
- workload consolidation
- dataplane operating systems
- microsecond-scale computing
- energy-proportionality
categories: []
date: '2016-12-01'
lastmod: 2022-05-15T13:35:13-07:00
featured: false
draft: false
venue: ACM TOCS

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
publishDate: '2022-05-15T20:35:13.522207Z'
publication_types:
- '2'
abstract: The conventional wisdom is that aggressive networking requirements, such
  as high packet rates for small messages and μs-scale tail latency, are best addressed
  outside the kernel, in a user-level networking stack. We present ix, a dataplane
  operating system that provides high I/O performance and high resource efficiency
  while maintaining the protection and isolation benefits of existing kernels.ix uses
  hardware virtualization to separate management and scheduling functions of the kernel
  (control plane) from network processing (dataplane). The dataplane architecture
  builds upon a native, zero-copy API and optimizes for both bandwidth and latency
  by dedicating hardware threads and networking queues to dataplane instances, processing
  bounded batches of packets to completion, and eliminating coherence traffic and
  multicore synchronization. The control plane dynamically adjusts core allocations
  and voltage/frequency settings to meet service-level objectives.We demonstrate that
  ix outperforms Linux and a user-space network stack significantly in both throughput
  and end-to-end latency. Moreover, ix improves the throughput of a widely deployed,
  key-value store by up to 6.4× and reduces tail latency by more than 2× . With three
  varying load patterns, the control plane saves 46%--54% of processor energy, and
  it allows background jobs to run at 35%--47% of their standalone throughput.
publication: '*ACM Transactions on Computer Systems*'
doi: 10.1145/2997641
---
