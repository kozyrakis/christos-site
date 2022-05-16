---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Mind the Gap: A Case for Informed Request Scheduling at the NIC'
subtitle: ''
summary: ''
authors:
- Jack Tigar Humphries
- Kostis Kaffes
- David Mazières
- admin
tags: []
categories: []
date: '2019-11-01'
lastmod: 2022-05-15T13:35:11-07:00
featured: false
draft: false
venue: HotNets'19

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
publishDate: '2022-05-15T20:35:11.068376Z'
publication_types:
- '1'
abstract: Recent research in high-throughput networked systems has established the
  need for centralized and preemptive request scheduling in order to achieve good
  hardware utilization and low tail latency for a wide variety of workloads. However,
  this approach is expensive to scale as it requires an increasing number of CPU cores
  dedicated to scheduling. Moreover, passing every request through a scheduling core
  introduces latency for inter-core communication and reduces the effectiveness of
  data preloading and caching optimizations.In this paper, we advocate in favor of
  pushing request-to-core scheduling back into the NIC. Instead of the simple request
  distribution of receive-side-scaling (RSS) in current NICs, we suggest implementing
  preemptive request scheduling by passing to the NIC up-to-date information about
  core availability and execution status of active requests. We present a prototype
  implementation on a commercial Smart-NIC that indeed shows performance benefits
  for different workload scenarios. The prototype allows us to also observe bottlenecks
  that largely come from artifacts of existing NIC hardware. We propose research towards
  addressing these limitations in order to achieve low overhead, low latency, and
  highly efficient request scheduling.
publication: '*Proceedings of the 18th ACM Workshop on Hot Topics in Networks (HotNets)*'
doi: 10.1145/3365609.3365856
---
