---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Flash Storage Disaggregation
subtitle: ''
summary: ''
authors:
- Ana Klimovic
- admin
- Eno Thereska
- Binu John
- Sanjeev Kumar
tags:
- network storage
- flash
- datacenter
categories: []
date: '2016-04-01'
lastmod: 2022-05-15T13:35:14-07:00
featured: false
draft: false
venue: Eurosys'16

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
publishDate: '2022-05-15T20:35:14.096389Z'
publication_types:
- '1'
abstract: PCIe-based Flash is commonly deployed to provide datacenter applications
  with high IO rates. However, its capacity and bandwidth are often underutilized
  as it is difficult to design servers with the right balance of CPU, memory and Flash
  resources over time and for multiple applications. This work examines Flash disaggregation
  as a way to deal with Flash overprovisioning. We tune remote access to Flash over
  commodity networks and analyze its impact on workloads sampled from real datacenter
  applications. We show that, while remote Flash access introduces a 20% throughput
  drop at the application level, disaggregation allows us to make up for these overheads
  through resource-efficient scale-out. Hence, we show that Flash disaggregation allows
  scaling CPU and Flash resources independently in a cost effective manner. We use
  our analysis to draw conclusions about data and control plane issues in remote storage.
publication: '*Proceedings of the 11th European Conference on Computer Systems (EuroSys)*'
doi: 10.1145/2901318.2901337
---
