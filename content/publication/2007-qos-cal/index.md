---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'From Chaos to QoS: Case Studies in CMP Resource Management'
subtitle: ''
summary: ''
authors:
- Fei Guo
- Hari Kannan
- Li Zhao
- Ramesh Illikkal
- Ravi Iyer
- Don Newell
- Yan Solihin
- admin
tags: []
categories: []
date: '2007-03-01'
lastmod: 2022-05-15T13:35:22-07:00
featured: false
draft: false
venue: IEEE CAL

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
publishDate: '2022-05-15T20:35:22.230042Z'
publication_types:
- '2'
abstract: As more and more cores are enabled on the die of future CMP platforms, we
  expect that several diverse workloads will run simultaneously on the platform. A
  key example of this trend is the growth of virtualization usage models. When multiple
  virtual machines or applications or threads run simultaneously, the quality of service
  (QoS) that the platform provides to each individual thread is non-deterministic
  today. This occurs because the simultaneously running threads place very different
  demands on the shared resources (cache space, memory bandwidth, etc) in the platform
  and in most cases contend with each other. In this paper, we first present case
  studies that show how this results in non-deterministic performance. Unlike the
  compute resources managed through scheduling, platform resource allocation to individual
  threads cannot be controlled today. In order to provide better determinism and QoS,
  we then examine resource management mechanisms and present QoS-aware architectures
  and execution environments. The main contribution of this paper is the architecture
  feasibility analysis through prototypes that allow experimentation with QoS-Aware
  execution environments and architectural resources. We describe these QoS prototypes
  and then present preliminary case studies of multi-tasking and virtualization usage
  models sharing one critical CMP resource (last-level cache). We then demonstrate
  how proper management of the cache resource can provide service differentiation
  and deterministic performance behavior when running disparate workloads in future
  CMP platforms.
publication: '*SIGARCH Computer Architure News*'
doi: 10.1145/1241601.1241608
---
