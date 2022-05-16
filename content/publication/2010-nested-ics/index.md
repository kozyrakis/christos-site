---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Making Nested Parallel Transactions Practical Using Lightweight Hardware Support
subtitle: ''
summary: ''
authors:
- Woongki Baek
- Nathan Bronson
- admin
- Kunle Olukotun
tags:
- transactional memory
- parallel programming
- nested parallelism
categories: []
date: '2010-06-01'
lastmod: 2022-05-15T13:35:18-07:00
featured: false
draft: false
venue: ICS'10

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
publishDate: '2022-05-15T20:35:18.515106Z'
publication_types:
- '1'
abstract: Transactional Memory (TM) simplifies parallel programming by supporting
  parallel tasks that execute in an atomic and isolated way. To achieve the best possible
  performance, TM must support the nested parallelism available in real-world applications
  and supported by popular programming models. A few recent papers have proposed support
  for nested parallelism in software TM (STM) and hardware TM (HTM). However, the
  proposed designs are still impractical, as they either introduce excessive runtime
  overheads or require complex hardware structures.This paper presents filter-accelerated,
  nested TM (FaNTM). We extend a hybrid TM based on hardware signatures to provide
  practical support for nested parallel transactions. In the FaNTM design, hardware
  filters provide continuous and nesting-aware conflict detection, which effectively
  eliminates the excessive overheads of software nested transactions. In contrast
  to a full HTM approach, FaNTM simplifies hardware by decoupling nested parallel
  transactions from caches using hardware filters. We also describe subtle correctness
  and liveness issues that do not exist in the non-nested baseline TM.We quantify
  the performance of FaNTM using STAMP applications and microbenchmarks that use concurrent
  data structures. First, we demonstrate that the runtime overhead of FaNTM is small
  (2.3% on average) when applications use only single-level parallelism. Second, we
  show that the incremental performance overhead of FaNTM is reasonable when the available
  parallelism is used in deeper nesting levels. We also demonstrate that nested parallel
  transactions on FaNTM run significantly faster (e.g., 12.4x) than those on a nested
  STM. Finally, we show how nested parallelism is used to improve the overall performance
  of a transactional microbenchmark.
publication: '*Proceedings of the 24th ACM International Conference on Supercomputing
  (ICS)*'
doi: 10.1145/1810085.1810097
---
