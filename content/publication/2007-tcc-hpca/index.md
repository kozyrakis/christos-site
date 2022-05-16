---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Scalable, Non-Blocking Approach to Transactional Memory
subtitle: ''
summary: ''
authors:
- Hassan Chafi
- Jared Casper
- Brian D. Carlstrom
- Austen McDonald
- Chi Cao Minh
- Woongki Baek
- admin
- Kunle Olukotun
tags: []
categories: []
date: '2007-02-01'
lastmod: 2022-05-15T13:35:22-07:00
featured: false
draft: false
venue: HPCA'07

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
publishDate: '2022-05-15T20:35:21.983054Z'
publication_types:
- '1'
abstract: Transactional Memory (TM) provides mechanisms that promise to simplify parallel
  programming by eliminating the need for locks and their associated problems (dead-lock,
  livelock, priority inversion, convoying). For TM to be adopted in the long term,
  not only does it need to deliver on these promises, but it needs to scale to a high
  number of processors. To date, proposals for scalable TM have relegated livelock
  issues to user-level contention managers. This paper presents the first scalable
  TM implementation for directory-based distributed shared memory systems that is
  livelock free without the need for user-level intervention. The design is a scalable
  implementation of optimistic concurrency control that supports parallel commits
  with a two-phase commit protocol, uses write-back caches, and filters coherence
  messages. The scalable design is based on Transactional Coherence and Consistency
  (TCC), which supports continuous transactions and fault isolation. A performance
  evaluation of the design using both scientific and enterprise benchmarks demonstrates
  that the directory-based TCC design scales efficiently for NUMA systems up to 64
  processors.
publication: '*Proceedings of the IEEE 13th International Symposium on High Performance
  Computer Architecture (HPCA)*'
doi: 10.1109/HPCA.2007.346189
---
