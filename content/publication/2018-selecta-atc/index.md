---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Selecta: Heterogeneous Cloud Storage Configuration for Data Analytics'
subtitle: ''
summary: ''
authors:
- Ana Klimovic
- Heiner Litz
- admin
tags: []
categories: []
date: '2018-07-01'
lastmod: 2022-05-15T13:35:12-07:00
featured: false
draft: false
venue: ATC'18

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
publishDate: '2022-05-15T20:35:12.211187Z'
publication_types:
- '1'
abstract: Data analytics are an important class of data-intensive workloads on public
  cloud services. However, selecting the right compute and storage configuration for
  these applications is difficult as the space of available options is large and the
  interactions between options are complex. Moreover, the different data streams accessed
  by analytics workloads have distinct characteristics that may be better served by
  different types of storage devices.We present Selecta, a tool that recommends near-optimal
  configurations of cloud compute and storage resources for data analytics workloads.
  Selecta uses latent factor collaborative filtering to predict how an application
  will perform across different configurations, based on sparse data collected by
  profiling training workloads. We evaluate Selecta with over one hundred Spark SQL
  and ML applications, showing that Selecta chooses a near-optimal performance configuration
  (within 10% of optimal) with 94% probability and a near-optimal cost configuration
  with 80% probability. We also use Selecta to draw significant insights about cloud
  storage systems, including the performance-cost efficiency of NVMe Flash devices,
  the need for cloud storage with support for fine-grain capacity and bandwidth allocation,
  and the motivation for end-to-end storage optimizations.
publication: '*Proceedings of the Usenix Annual Technical Conference (ATC)*'
---
