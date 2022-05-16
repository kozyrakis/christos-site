---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'iBench: Quantifying interference for datacenter applications'
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- admin
tags:
- Interference;Benchmark testing;Bandwidth;Kernel;Servers;Sensitivity;Prefetching
categories: []
date: '2013-09-01'
lastmod: 2022-05-15T13:35:15-07:00
featured: false
draft: false
venue: IISWC'13

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
publishDate: '2022-05-15T20:35:15.484853Z'
publication_types:
- '1'
abstract: Interference between co-scheduled applications is one of the major reasons
  that causes modern datacenters (DCs) to operate at low utilization. DC operators
  traditionally side-step interference either by disallowing colocation altogether
  and providing isolated server instances, or by requiring the users to express resource
  reservations, which are often exaggerated to counter-balance the unpredictability
  in the quality of allocated resources. Understanding, reducing and managing interference
  can significantly impact the manner in which these large-scale systems operate.
  We present iBench, a novel workload suite that helps quantify the pressure different
  applications put in various shared resources, and similarly the pressure they can
  tolerate in these resources. iBench consists of a set of carefully-crafted benchmarks
  that induce interference of increasing intensity in resources that span the CPU,
  cache hierarchy, memory, storage and networking subsystems. We first validate the
  effect that iBench workloads have on performance against a wide spectrum of DC applications.
  Then, we use iBench to demonstrate the importance of considering interference in
  a set of challenging problems that range from DC scheduling and server provisioning,
  to resource-efficient application development and scheduling for heterogeneous CMPs.
  In all cases quantifying interference with iBench results in significant performance
  and/or efficiency improvements. We plan to release iBench under a free software
  license.
publication: '*2013 IEEE International Symposium on Workload Characterization (IISWC)*'
doi: 10.1109/IISWC.2013.6704667
---
