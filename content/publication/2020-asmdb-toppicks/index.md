---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'AsmDB: Understanding and Mitigating Front-End Stalls in Warehouse-Scale Computers'
subtitle: ''
summary: ''
authors:
- Nayana Prasad Nagendra
- Grant Ayers
- David I. August
- Hyoun Kyu Cho
- Svilen Kanev
- admin
- Trivikram Krishnamurthy
- Heiner Litz
- Tipp Moseley
- Parthasarathy Ranganathan
tags:
- Prefetching;Optimization;Servers;Hardware;Databases;Complexity theory
categories: []
date: '2020-05-01'
lastmod: 2022-05-15T13:35:10-07:00
featured: false
draft: false
venue: Top Picks'20

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
publishDate: '2022-05-15T20:35:10.504446Z'
publication_types:
- '2'
abstract: It is well known that the datacenters hosting today's cloud services waste
  a significant number of cycles on front-end stalls. However, prior work has provided
  little insights about the source of these front-end stalls and how to address them.
  This work analyzes the cause of instruction cache misses at a fleet-wide scale and
  proposes a new compiler-driven software code prefetching strategy to reduce instruction
  caches misses by 90%.
publication: '*IEEE Micro*'
doi: 10.1109/MM.2020.2986212
---
