---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Centralized Core-Granular Scheduling for Serverless Functions
subtitle: ''
summary: ''
authors:
- Kostis Kaffes
- Neeraja J. Yadwadkar
- admin
tags:
- scheduling
- cloud computing
- serverless computing
- resource allocation
categories: []
date: '2019-08-01'
lastmod: 2022-05-15T13:35:10-07:00
featured: false
draft: false
venue: SoCC'19

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
publishDate: '2022-05-15T20:35:10.906307Z'
publication_types:
- '1'
abstract: 'In recent years, many applications have started using serverless computing
  platforms primarily due to the ease of deployment and cost efficiency they offer.
  However, the existing scheduling mechanisms of serverless platforms fall short in
  catering to the unique characteristics of such applications: burstiness, short and
  variable execution times, statelessness and use of a single core. Specifically,
  the existing mechanisms fall short in meeting the requirements generated due to
  the combined effect of these characteristics: scheduling at a scale of millions
  of function invocations per second while achieving predictable performance.In this
  paper, we argue for a cluster-level centralized and core-granular scheduler for
  serverless functions. By maintaining a global view of the cluster resources, the
  centralized approach eliminates queue imbalances while the core granularity reduces
  interference; together these properties enable reduced performance variability.
  We expect such a scheduler to increase the adoption of serverless computing platforms
  by various latency and throughput sensitive applications.'
publication: '*Proceedings of the ACM Symposium on Cloud Computing (SoCC)*'
doi: 10.1145/3357223.3362709
---
