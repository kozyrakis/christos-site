---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'ReFlex: Remote Flash ≈ Local Flash'
subtitle: ''
summary: ''
authors:
- Ana Klimovic
- Heiner Litz
- admin
tags:
- flash
- i/o scheduling
- network storage
- qos
- datacenter storage
categories: []
date: '2017-04-01'
lastmod: 2022-05-15T13:35:13-07:00
featured: false
draft: false
venue: ASPLOS'17

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
publishDate: '2022-05-15T20:35:13.270260Z'
publication_types:
- '1'
abstract: Remote access to NVMe Flash enables flexible scaling and high utilization
  of Flash capacity and IOPS within a datacenter. However, existing systems for remote
  Flash access either introduce significant performance overheads or fail to isolate
  the multiple remote clients sharing each Flash device. We present ReFlex, a software-based
  system for remote Flash access, that provides nearly identical performance to accessing
  local Flash. ReFlex uses a dataplane kernel to closely integrate networking and
  storage processing to achieve low latency and high throughput at low resource requirements.
  Specifically, ReFlex can serve up to 850K IOPS per core over TCP/IP networking,
  while adding 21us over direct access to local Flash. ReFlex uses a QoS scheduler
  that can enforce tail latency and throughput service-level objectives (SLOs) for
  thousands of remote clients. We show that ReFlex allows applications to use remote
  Flash while maintaining their original performance with local Flash.
publication: '*Proceedings of the 22nd International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/3037697.3037732
---
