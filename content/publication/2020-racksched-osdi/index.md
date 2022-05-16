---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'RackSched: A Microsecond-Scale Scheduler for Rack-Scale Computers'
subtitle: ''
summary: ''
authors:
- Hang Zhu
- Kostis Kaffes
- Zixu Chen
- Zhenming Liu
- admin
- Ion Stoica
- Xin Jin
tags: []
categories: []
date: '2020-10-01'
lastmod: 2022-05-15T13:35:10-07:00
featured: false
draft: false
venue: OSDI'20

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
publishDate: '2022-05-15T20:35:10.179023Z'
publication_types:
- '1'
abstract: Low-latency online services have strict Service Level Objectives (SLOs)
  that require datacenter systems to support high throughput at microsecond-scale
  tail latency. Dataplane operating systems have been designed to scale up multicore
  servers with minimal overhead for such SLOs. However, as application demands continue
  to increase, scaling up is not enough, and serving larger demands requires these
  systems to scale out to multiple servers in a rack.We present RackSched, the first
  rack-level microsecond-scale scheduler that provides the abstraction of a rack-scale
  computer (i.e., a huge server with hundreds to thousands of cores) to an external
  service with network-system co-design. The core of RackSched is a two-layer scheduling
  framework that integrates inter-server scheduling in the top-of-rack (ToR) switch
  with intra-server scheduling in each server. We use a combination of analytical
  results and simulations to show that it provides near-optimal performance as centralized
  scheduling policies, and is robust for both low-dispersion and high-dispersion workloads.
  We design a custom switch data plane for the inter-server scheduler, which realizes
  power-of-k-choices, ensures request affinity, and tracks server loads accurately
  and efficiently. We implement a RackSched prototype on a cluster of commodity servers
  connected by a Barefoot Tofino switch. End-to-end experiments on a twelve-server
  testbed show that RackSched improves the throughput by up to 1.44×, and scales out
  the throughput near linearly, while maintaining the same tail latency as one server
  until the system is saturated.
publication: '*Proceedings of the 14th USENIX Conference on Operating Systems Design
  and Implementation (OSDI)*'
---
