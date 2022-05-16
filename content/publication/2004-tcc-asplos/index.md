---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Programming with Transactional Coherence and Consistency (TCC)
subtitle: ''
summary: ''
authors:
- Lance Hammond
- Brian D. Carlstrom
- Vicky Wong
- Ben Hertzberg
- Mike Chen
- admin
- Kunle Olukotun
tags:
- feedback optimization
- transactions
- multiprocessor architecture
categories: []
date: '2004-10-01'
lastmod: 2022-05-15T13:35:24-07:00
featured: false
draft: false
venue: ASPLOS'04

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
publishDate: '2022-05-15T20:35:24.780959Z'
publication_types:
- '1'
abstract: Transactional Coherence and Consistency (TCC) offers a way to simplify parallel
  programming by executing all code within transactions. In TCC systems, transactions
  serve as the fundamental unit of parallel work, communication and coherence. As
  each transaction completes, it writes all of its newly produced state to shared
  memory atomically, while restarting other processors that have speculatively read
  stale data. With this mechanism, a TCC-based system automatically handles data synchronization
  correctly, without programmer intervention. To gain the benefits of TCC, programs
  must be decomposed into transactions. We describe two basic programming language
  constructs for decomposing programs into transactions, a loop conversion syntax
  and a general transaction-forking mechanism. With these constructs, writing correct
  parallel programs requires only small, incremental changes to correct sequential
  programs. The performance of these programs may then easily be optimized, based
  on feedback from real program execution, using a few simple techniques.
publication: '*Proceedings of the 11th International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/1024393.1024395
---
