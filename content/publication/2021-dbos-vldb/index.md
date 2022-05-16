---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'DBOS: A DBMS-Oriented Operating System'
subtitle: ''
summary: ''
authors:
- Athinagoras Skiadopoulos
- Qian Li
- Peter Kraft
- Kostis Kaffes
- Daniel Hong
- Shana Mathew
- David Bestor
- Michael Cafarella
- Vijay Gadepally
- Goetz Graefe
- Jeremy Kepner
- admin
- Tim Kraska
- Michael Stonebraker
- Lalith Suresh
- Matei Zaharia
tags: []
categories: []
date: '2021-09-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue: VLDB'22

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
publishDate: '2022-05-15T20:35:09.772238Z'
publication_types:
- '1'
abstract: This paper lays out the rationale for building a completely new operating
  system (OS) stack. Rather than build on a single node OS together with separate
  cluster schedulers, distributed filesystems, and network managers, we argue that
  a distributed transactional DBMS should be the basis for a scalable cluster OS.
  We show herein that such a database OS (DBOS) can do scheduling, file management,
  and inter-process communication with competitive performance to existing systems.
  In addition, significantly better analytics can be provided as well as a dramatic
  reduction in code complexity through implementing OS services as standard database
  queries, while implementing low-latency transactions and high availability only
  once.
publication: '*Proceedings of the VLDB Endowment (VLDB)*'
doi: 10.14778/3485450.3485454
---
