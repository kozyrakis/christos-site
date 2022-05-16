---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Leveraging Application Classes to Save Power in Highly-Utilized Data Centers
subtitle: ''
summary: ''
authors:
- Kostis Kaffes
- Dragos Sbirlea
- Yiyan Lin
- David Lo
- admin
tags: []
categories: []
date: '2020-08-01'
lastmod: 2022-05-15T13:35:10-07:00
featured: false
draft: false
venue: SoCC'20

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
publishDate: '2022-05-15T20:35:10.259125Z'
publication_types:
- '1'
abstract: Data center energy consumption has become an increasingly significant contributor
  both to greenhouse emissions and costs. To increase utilization of individual hosts
  and improve efficiency, most modern data centers co-locate workloads belonging to
  different application classes, some being latency-sensitive (LS) and others best-effort
  (BE) which are more tolerant to performance variation. It is therefore necessary
  to design mechanisms that reduce power consumption even in the resulting high-utilization
  environment, while preserving LS task performance. Moreover, the abundance of different
  workloads and the security implications of public cloud make mechanisms that rely
  on extensive knowledge of workload characteristics or on application-exported metrics
  challenging to deploy.We present PACT, Per Application Class Turbo Controller, a
  system that leverages two novel mechanisms to reduce power consumption even in highly-utilized
  data centers. By treating applications like opaque boxes that do not need to provide
  application-specific performance signals, the first mechanism, Turbo Control, reduces
  power consumption by decreasing the operating frequency and throttling only BE tasks,
  without affecting performance-sensitive LS tasks. We identify the shortcomings of
  Turbo Control and increase its effectiveness by introducing CPUJailing, a mechanism
  that allocates different sets of cores to LS and BE applications. We deploy PACT
  (Turbo Control + CPUJailing) in production at Google's data centers and demonstrate
  that it provides workload-agnostic power savings of 9% on average together with
  a 4% performance improvement for LS tasks across thousands of workloads and nodes.
publication: '*Proceedings of the 11th ACM Symposium on Cloud Computing (SoCC)*'
doi: 10.1145/3419111.3421274
---
