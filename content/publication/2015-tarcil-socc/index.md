---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Tarcil: Reconciling Scheduling Speed and Quality in Large Shared Clusters'
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- Daniel Sanchez
- admin
tags:
- scalability
- scheduling
- QoS
- cloud computing
- datacenters
- resource-efficiency
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
publishDate: '2022-05-15T20:35:14.586308Z'
publication_types:
- '1'
abstract: Scheduling diverse applications in large, shared clusters is particularly
  challenging. Recent research on cluster scheduling focuses either on scheduling
  speed, using sampling to quickly assign resources to tasks, or on scheduling quality,
  using centralized algorithms that search for the resources that improve both task
  performance and cluster utilization.We present Tarcil, a distributed scheduler that
  targets both scheduling speed and quality. Tarcil uses an analytically derived sampling
  framework that adjusts the sample size based on load, and provides statistical guarantees
  on the quality of allocated resources. It also implements admission control when
  sampling is unlikely to find suitable resources. This makes it appropriate for large,
  shared clusters hosting short- and long-running jobs. We evaluate Tarcil on clusters
  with hundreds of servers on EC2. For highly-loaded clusters running short jobs,
  Tarcil improves task execution time by 41% over a distributed, sampling-based scheduler.
  For more general scenarios, Tarcil achieves near-optimal performance for 4× and
  2× more jobs than sampling-based and centralized schedulers respectively.
publication: '*Proceedings of the 6th ACM Symposium on Cloud Computing (SOCC)*'
doi: 10.1145/2806777.2806779
---
