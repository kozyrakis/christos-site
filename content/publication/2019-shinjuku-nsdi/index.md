---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Shinjuku: Preemptive Scheduling for µSecond-Scale Tail Latency'
subtitle: ''
summary: ''
authors:
- Kostis Kaffes
- Timothy Chong
- Jack Tigar Humphries
- Adam Belay
- David Mazières
- admin
tags: []
categories: []
date: '2019-02-01'
lastmod: 2022-05-15T13:35:11-07:00
featured: false
draft: false
venue: NSDI'19

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
publishDate: '2022-05-15T20:35:11.556392Z'
publication_types:
- '1'
abstract: The recently proposed dataplanes for microsecond scale applications, such
  as IX and ZygOS, use nonpreemptive policies to schedule requests to cores. For the
  many real-world scenarios where request service times follow distributions with
  high dispersion or a heavy tail, they allow short requests to be blocked behind
  long requests, which leads to poor tail latency.Shinjuku is a single-address space
  operating system that uses hardware support for virtualization to make preemption
  practical at the microsecond scale. This allows Shinjuku to implement centralized
  scheduling policies that preempt requests as often as every 5µsec and work well
  for both light and heavy tailed request service time distributions. We demonstrate
  that Shinjuku provides significant tail latency and throughput improvements over
  IX and ZygOS for a wide range of workload scenarios. For the case of a RocksDB server
  processing both point and range queries, Shinjuku achieves up to 6.6× higher throughput
  and 88% lower tail latency.
publication: '*Proceedings of the 16th USENIX Conference on Networked Systems Design
  and Implementation (NSDI)*'
---
