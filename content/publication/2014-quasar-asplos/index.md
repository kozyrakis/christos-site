---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Quasar: Resource-Efficient and QoS-Aware Cluster Management'
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- admin
tags:
- resource efficiency
- resource allocation and assignment
- quality of service
- cloud computing
- datacenters
- cluster management
categories: []
date: '2014-03-01'
lastmod: 2022-05-15T13:35:15-07:00
featured: false
draft: false
venue: ASPLOS'14

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
publishDate: '2022-05-15T20:35:15.402502Z'
publication_types:
- '1'
abstract: Cloud computing promises flexibility and high performance for users and
  high cost-efficiency for operators. Nevertheless, most cloud facilities operate
  at very low utilization, hurting both cost effectiveness and future scalability.We
  present Quasar, a cluster management system that increases resource utilization
  while providing consistently high application performance. Quasar employs three
  techniques. First, it does not rely on resource reservations, which lead to underutilization
  as users do not necessarily understand workload dynamics and physical resource requirements
  of complex codebases. Instead, users express performance constraints for each workload,
  letting Quasar determine the right amount of resources to meet these constraints
  at any point. Second, Quasar uses classification techniques to quickly and accurately
  determine the impact of the amount of resources (scale-out and scale-up), type of
  resources, and interference on performance for each workload and dataset. Third,
  it uses the classification results to jointly perform resource allocation and assignment,
  quickly exploring the large space of options for an efficient way to pack workloads
  on available resources. Quasar monitors workload performance and adjusts resource
  allocation and assignment when needed. We evaluate Quasar over a wide range of workload
  scenarios, including combinations of distributed analytics frameworks and low-latency,
  stateful services, both on a local cluster and a cluster of dedicated EC2 servers.
  At steady state, Quasar improves resource utilization by 47% in the 200-server EC2
  cluster, while meeting performance constraints for workloads of all types.
publication: '*Proceedings of the 19th International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/2541940.2541941
---
