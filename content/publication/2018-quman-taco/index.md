---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'QuMan: Profile-Based Improvement of Cluster Utilization'
subtitle: ''
summary: ''
authors:
- Yannis Sfakianakis
- Christos Kozanitis
- admin
- Angelos Bilas
tags:
- Resource management
- slices
- I/O caching
- isolation
- input/output
- solid state disk
categories: []
date: '2018-08-01'
lastmod: 2022-05-15T13:35:11-07:00
featured: false
draft: false
venue: ACM TACO
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
publishDate: '2022-05-15T20:35:11.796945Z'
publication_types:
- '2'
abstract: 'Modern data centers consolidate workloads to increase server utilization
  and reduce total cost of ownership, and cope with scaling limitations. However,
  server resource sharing introduces performance interference across applications
  and, consequently, increases performance volatility, which negatively affects user
  experience. Thus, a challenging problem is to increase server utilization while
  maintaining application QoS.In this article, we present QuMan, a server resource
  manager that uses application isolation and profiling to increase server utilization
  while controlling degradation of application QoS. Previous solutions, either estimate
  interference across applications and then restrict colocation to “compatible” applications,
  or assume that application requirements are known. Instead, QuMan estimates the
  required resources of applications. It uses an isolation mechanism to create properly-sized
  resource slices for applications, and arbitrarily colocates applications. QuMan’s
  mechanisms can be used with a variety of admission control policies, and we explore
  the potential of two such policies: (1) A policy that allows users to specify a
  minimum performance threshold and (2) an automated policy, which operates without
  user input and is based on a new combined QoS-utilization metric. We implement QuMan
  on top of Linux servers, and we evaluate its effectiveness using containers and
  real applications. Our single-node results show that QuMan balances highly effectively
  the tradeoff between server utilization and application performance, as it achieves
  80% server utilization while the performance of each application does not drop below
  80% the respective standalone performance. We also deploy QuMan on a cluster of
  100 AWS instances that are managed by a modified version of the Sparrow scheduler
  [37] and, we observe a 48% increase in application performance on a highly utilized
  cluster, compared to the performance of the same cluster under the same load when
  it is managed by native Sparrow or Apache Mesos.'
publication: '*ACM Transactions on Architecture and Code Optimization*'
doi: 10.1145/3210560
---
