---
# Documentation: https://wowchemy.com/docs/managing-content/

title: On the Energy (in)Efficiency of Hadoop Clusters
subtitle: ''
summary: ''
authors:
- Jacob Leverich
- admin
tags: []
categories: []
date: '2010-03-01'
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
publishDate: '2022-05-15T20:35:19.350530Z'
publication_types:
- '2'
abstract: Distributed processing frameworks, such as Yahoo!'s Hadoop and Google's
  MapReduce, have been successful at harnessing expansive datacenter resources for
  large-scale data analysis. However, their effect on datacenter energy efficiency
  has not been scrutinized. Moreover, the filesystem component of these frameworks
  effectively precludes scale-down of clusters deploying these frameworks (i.e. operating
  at reduced capacity). This paper presents our early work on modifying Hadoop to
  allow scale-down of operational clusters. We find that running Hadoop clusters in
  fractional configurations can save between 9% and 50% of energy consumption, and
  that there is a tradeoff between performance energy consumption. We also outline
  further research into the energy-efficiency of these frameworks.
publication: '*SIGOPS Operating Systems Review*'
doi: 10.1145/1740390.1740405
---
