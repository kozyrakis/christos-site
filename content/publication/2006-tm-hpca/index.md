---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The common case transactional behavior of multithreaded programs
subtitle: ''
summary: ''
authors:
- JaeWoong Chung
- Hassan Chafi
- Chi Cao Minh
- Austen McDonald
- Brian Carlstrom
- admin
- Kunle Olukotun
tags:
- Computer aided software engineering;Frequency synchronization;Application software;Concurrent
  computing;Parallel programming;Hardware;Proposals;Programming profession;System
  recovery;Robustness
categories: []
date: '2006-02-01'
lastmod: 2022-05-15T13:35:23-07:00
featured: false
draft: false
venue: HPCA'06

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
publishDate: '2022-05-15T20:35:23.708882Z'
publication_types:
- '1'
abstract: Transactional memory (TM) provides an easy-to-use and high-performance parallel
  programming model for the upcoming chip-multiprocessor systems. Several researchers
  have proposed alternative hardware and software TM implementations. However, the
  lack of transaction-based programs makes it difficult to understand the merits of
  each proposal and to tune future TM implementations to the common case behavior
  of real application. This work addresses this problem by analyzing the common case
  transactional behavior for 35 multithreaded programs from a wide range of application
  domains. We identify transactions within the source code by mapping existing primitives
  for parallelism and synchronization management to transaction boundaries. The analysis
  covers basic characteristics such as transaction length, distribution of read-set
  and write-set size, and the frequency of nesting and I/O operations. The measured
  characteristics provide key insights into the design of efficient TM systems for
  both non-blocking synchronization and speculative parallelization.
publication: '*Proceedings of the 12th International Symposium on High-Performance
  Computer Architecture (HPCA)*'
doi: 10.1109/HPCA.2006.1598135
---
