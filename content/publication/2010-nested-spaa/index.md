---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Implementing and Evaluating Nested Parallel Transactions in Software Transactional
  Memory
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
venue: SPAA'10

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
publishDate: '2022-05-15T20:35:18.433724Z'
publication_types:
- '1'
abstract: Transactional Memory (TM) is a promising technique that simplifies parallel
  programming for shared-memory applications. To date, most TM systems have been designed
  to efficiently support single-level parallelism. To achieve widespread use and maximize
  performance gains, TM must support nested parallelism available in many applications
  and supported by several programming models.We present NesTM, a software TM (STM)
  system that supports closed-nested parallel transactions. NesTM is based on a high-performance,
  blocking STM that uses eager version management and word-granularity conflict detection.
  Its algorithm targets the state and runtime overheads of nested parallel transactions.
  We also describe several subtle correctness issues in supporting nested parallel
  transactions in NesTM and discuss their performance impact.Through our evaluation,
  we quantitatively analyze the performance of NesTM using STAMP applications and
  microbenchmarks based on concurrent data structures. First, we show that the performance
  overhead of NesTM is reasonable when single-level parallelism is used. Second, we
  quantify the incremental overhead of NesTM when the parallelism is exploited in
  deeper nesting levels and draw conclusions that can be useful in designing a nesting-aware
  TM runtime environment. Finally, we demonstrate a use-case where nested parallelism
  improves the performance of a transactional microbenchmark.
publication: '*Proceedings of the 22nd ACM Symposium on Parallelism in Algorithms
  and Architectures (SPAA)*'
doi: 10.1145/1810479.1810528
---
