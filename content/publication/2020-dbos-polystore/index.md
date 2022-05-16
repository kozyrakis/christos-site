---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Polystore Based Database Operating System (DBOS)
subtitle: ''
summary: ''
authors:
- Michael Cafarella
- David DeWitt
- Vijay Gadepally
- Jeremy Kepner
- admin
- Tim Kraska
- Michael Stonebraker
- Matei Zaharia
tags: []
categories: []
date: '2020-01-01'
lastmod: 2022-05-15T13:35:10-07:00
featured: false
draft: false
venue: Poly'20

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
publishDate: '2022-05-15T20:35:10.341088Z'
publication_types:
- '1'
abstract: 'Current operating systems are complex systems that were designed before
  today’s computing environments. This makes it difficult for them to meet the scalability,
  heterogeneity, availability, and security challenges in current cloud and parallel
  computing environments. To address these problems, we propose a radically new OS
  design based on data-centric architecture: all operating system state should be
  represented uniformly as database tables, and operations on this state should be
  made via queries from otherwise stateless tasks. This design makes it easy to scale
  and evolve the OS without whole-system refactoring, inspect and debug system state,
  upgrade components without downtime, manage decisions using machine learning, and
  implement sophisticated security features. We discuss how a database OS (DBOS) can
  improve the programmability and performance of many of today’s most important applications
  and propose a plan for the development of a DBOS proof of concept.'
publication: '*Heterogeneous Data Management, Polystores, and Analytics for Healthcare: VLDB Workshops (Poly 2020)*'
doi: 10.1007/978-3-030-71055-2_1
---
