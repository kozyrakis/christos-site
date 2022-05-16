---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Paragon: QoS-Aware Scheduling for Heterogeneous Datacenters'
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- admin
tags:
- interference
- cloud computing
- datacenter
- scheduling
- qos
- heterogeneity
categories: []
date: '2013-03-01'
lastmod: 2022-05-15T13:35:16-07:00
featured: false
draft: false
venue: ASPLOS'13

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
publishDate: '2022-05-15T20:35:16.223507Z'
publication_types:
- '1'
abstract: Large-scale datacenters (DCs) host tens of thousands of diverse applications
  each day. However, interference between colocated workloads and the difficulty to
  match applications to one of the many hardware platforms available can degrade performance,
  violating the quality of service (QoS) guarantees that many cloud workloads require.
  While previous work has identified the impact of heterogeneity and interference,
  existing solutions are computationally intensive, cannot be applied online and do
  not scale beyond few applications.We present Paragon, an online and scalable DC
  scheduler that is heterogeneity and interference-aware. Paragon is derived from
  robust analytical methods and instead of profiling each application in detail, it
  leverages information the system already has about applications it has previously
  seen. It uses collaborative filtering techniques to quickly and accurately classify
  an unknown, incoming workload with respect to heterogeneity and interference in
  multiple shared resources, by identifying similarities to previously scheduled applications.
  The classification allows Paragon to greedily schedule applications in a manner
  that minimizes interference and maximizes server utilization. Paragon scales to
  tens of thousands of servers with marginal scheduling overheads in terms of time
  or state.We evaluate Paragon with a wide range of workload scenarios, on both small
  and large-scale systems, including 1,000 servers on EC2. For a 2,500-workload scenario,
  Paragon enforces performance guarantees for 91% of applications, while significantly
  improving utilization. In comparison, heterogeneity-oblivious, interference-oblivious
  and least-loaded schedulers only provide similar guarantees for 14%, 11% and 3%
  of workloads. The differences are more striking in oversubscribed scenarios where
  resource efficiency is more critical.
publication: '*Proceedings of the 18th International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/2451116.2451125
---
