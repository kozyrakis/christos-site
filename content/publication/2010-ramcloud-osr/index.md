---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The Case for RAMClouds: Scalable High-Performance Storage Entirely in DRAM'
subtitle: ''
summary: ''
authors:
- John Ousterhout
- Parag Agrawal
- David Erickson
- admin
- Jacob Leverich
- David Mazières
- Subhasish Mitra
- Aravind Narayanan
- Guru Parulkar
- Mendel Rosenblum
- Stephen M. Rumble
- Eric Stratmann
- Ryan Stutsman
tags: []
categories: []
date: '2010-01-01'
lastmod: 2022-05-15T13:35:19-07:00
featured: false
draft: false
venue: Usenix OSR

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
publishDate: '2022-05-15T20:35:19.184436Z'
publication_types:
- '2'
abstract: 'Disk-oriented approaches to online storage are becoming increasingly problematic:
  they do not scale gracefully to meet the needs of large-scale Web applications,
  and improvements in disk capacity have far outstripped improvements in access latency
  and bandwidth. This paper argues for a new approach to datacenter storage called
  RAMCloud, where information is kept entirely in DRAM and large-scale systems are
  created by aggregating the main memories of thousands of commodity servers. We believe
  that RAMClouds can provide durable and available storage with 100-1000x the throughput
  of disk-based systems and 100-1000x lower access latency. The combination of low
  latency and large scale will enable a new breed of dataintensive applications.'
publication: '*SIGOPS Operating Systems Review (OSR)*'
doi: 10.1145/1713254.1713276
---
