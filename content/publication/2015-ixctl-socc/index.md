---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Energy Proportionality and Workload Consolidation for Latency-Critical Applications
subtitle: ''
summary: ''
authors:
- George Prekas
- Mia Primorac
- Adam Belay
- admin
- Edouard Bugnion
tags:
- energy proportionality
- microsecond-scale computing
- workload consolidation
- latency-critical applications
categories: []
date: '2015-08-01'
lastmod: 2022-05-15T13:35:14-07:00
featured: false
draft: false
venue: SoCC'15

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
publishDate: '2022-05-15T20:35:14.503488Z'
publication_types:
- '1'
abstract: Energy proportionality and workload consolidation are important objectives
  towards increasing efficiency in large-scale datacenters. Our work focuses on achieving
  these goals in the presence of applications with μs-scale tail latency requirements.
  Such applications represent a growing subset of datacenter workloads and are typically
  deployed on dedicated servers, which is the simplest way to ensure low tail latency
  across all loads. Unfortunately, it also leads to low energy efficiency and low
  resource utilization during the frequent periods of medium or low load.We present
  the OS mechanisms and dynamic control needed to adjust core allocation and voltage/frequency
  settings based on the measured delays for latency-critical workloads. This allows
  for energy proportionality and frees the maximum amount of resources per server
  for other background applications, while respecting service-level objectives. Monitoring
  hardware queue depths allows us to detect increases in queuing latencies. Carefully
  coordinated adjustments to the NIC's packet redirection table enable us to reassign
  flow groups between the threads of a latency-critical application in milliseconds
  without dropping or reordering packets. We compare the efficiency of our solution
  to the Pareto-optimal frontier of 224 distinct static configurations. Dynamic resource
  control saves 44%--54% of processor energy, which corresponds to 85%--93% of the
  Pareto-optimal upper bound. Dynamic resource control also allows background jobs
  to run at 32%--46% of their standalone throughput, which corresponds to 82%--92%
  of the Pareto bound.
publication: '*Proceedings of the 6th ACM Symposium on Cloud Computing (SOCC)*'
doi: 10.1145/2806777.2806848
---
