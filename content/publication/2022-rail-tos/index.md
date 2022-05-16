---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'RAIL: Predictable, Low Tail Latency for NVMe Flash'
subtitle: ''
summary: ''
authors:
- Heiner Litz
- Javier Gonzalez
- Ana Klimovic
- admin
tags:
- LightNVM
- Linux
- SSD
- OpenChannel
categories: []
date: '2022-02-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue : ACM TOS

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
publishDate: '2022-05-15T20:35:09.030602Z'
publication_types:
- '2'
abstract: Flash-based storage is replacing disk for an increasing number of data center
  applications, providing orders of magnitude higher throughput and lower average
  latency. However, applications also require predictable storage latency. Existing
  Flash devices fail to provide low tail read latency in the presence of write operations.
  We propose two novel techniques to address SSD read tail latency, including Redundant
  Array of Independent LUNs (RAIL) which avoids serialization of reads behind user
  writes as well as latency-aware hot-cold separation (HC) which improves write throughput
  while maintaining low tail latency. RAIL leverages the internal parallelism of modern
  Flash devices and allocates data and parity pages to avoid reads getting stuck behind
  writes. We implement RAIL in the Linux Kernel as part of the LightNVM Flash translation
  layer and show that it can reduce read tail latency by 7× at the 99.99th percentile,
  while reducing relative bandwidth by only 33%.
publication: '*ACM Transactions on Storage*'
doi: 10.1145/3465406
---
