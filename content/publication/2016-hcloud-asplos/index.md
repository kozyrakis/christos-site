---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'HCloud: Resource-Efficient Provisioning in Shared Cloud Systems'
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- admin
tags:
- datacenter
- cloud computing
- latency
- hybrid
- resource efficiency
- QoS
- provisioning
categories: []
date: '2016-04-01'
lastmod: 2022-05-15T13:35:14-07:00
featured: false
draft: false
venue: ASPLOS'16

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
publishDate: '2022-05-15T20:35:14.260543Z'
publication_types:
- '1'
abstract: Cloud computing promises flexibility and high performance for users and
  cost efficiency for operators. To achieve this, cloud providers offer instances
  of different sizes, both as long-term reservations and short-term, on-demand allocations.
  Unfortunately, determining the best provisioning strategy is a complex, multi-dimensional
  problem that depends on the load fluctuation and duration of incoming jobs, and
  the performance unpredictability and cost of resources. We first compare the two
  main provisioning strategies (reserved and on-demand resources) on Google Compute
  Engine (GCE) using three representative workload scenarios with batch and latency-critical
  applications. We show that either approach is suboptimal for performance or cost.
  We then present HCloud, a hybrid provisioning system that uses both reserved and
  on-demand resources. HCloud determines which jobs should be mapped to reserved versus
  on-demand resources based on overall load, and resource unpredictability. It also
  determines the optimal instance size an application needs to satisfy its Quality
  of Service (QoS) constraints. We demonstrate that hybrid configurations improve
  performance by 2.1x compared to fully on-demand provisioning, and reduce cost by
  46% compared to fully reserved systems. We also show that hybrid strategies are
  robust to variation in system and job parameters, such as cost and system load.
publication: '*Proceedings of the 21st International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/2872362.2872365
---
