---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Transactional Collection Classes
subtitle: ''
summary: ''
authors:
- Brian D. Carlstrom
- Austen McDonald
- Michael Carbin
- admin
- Kunle Olukotun
tags:
- collection classes
- multiprocessor architecture
- Java
- transactional memory
categories: []
date: '2007-03-01'
lastmod: 2022-05-15T13:35:21-07:00
featured: false
draft: false
venue: PPoPP'07


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
publishDate: '2022-05-15T20:35:21.816255Z'
publication_types:
- '1'
abstract: While parallel programmers find it easier to reason about large atomic regions,
  the conventional mutual exclusion-based primitives for synchronization force them
  to interleave many small operations to achieve performance. Transactional memory
  promises that programmer scan use large atomic regions while achieving similar performance.
  However, these large transactions can conflict when operating on shared data structures,
  even for logically independent operations. Transactional collection classes address
  this problem by allowing long-running transactions to operate on shared data while
  eliminating unnecessary conflicts. Transactional collection classes wrap existing
  data structures, without the need for custom implementations or knowledge of data
  structure internals.Without transactional collection classes, access to shared datafrom
  within long-running transactions can suffer from data dependency conflicts that
  are logically unnecessary, but are artifacts of the data structure implementation
  such as hash table collisions or tree-balancing rotations. Our transactional collection
  classes use the concept of semantic concurrency control to eliminate these unnecessary
  data dependencies, replacing them with conflict detection based on the operations
  of the abstract data type.The design and behavior of these transactional collection
  classes is discussed with reference to the related work from the database community
  such as multi-level transactions and semantic concurrency control, as well as other
  concurrent data structures such as java.util.concurrent. The required transactional
  semantics needed for implementing transactional collection are enumerated, including
  open-nested transactions and commit and abort handlers. We also discuss how isolation
  can be reduced for greater concurrency. Finally, we provide guidelines on the construction
  of classes that preserve isolation and serializability.The performance of these
  classes is evaluated with a number of benchmarks including targeted micro-benchmarks
  and a version of SPECjbb2000 with increased contention. The results show that easier-to-use
  long transactions can still allow programs to deliver scalable performance by simply
  wrapping existing data structures with transactional collection classes.
publication: '*Proceedings of the 12th ACM SIGPLAN Symposium on Principles and Practice
  of Parallel Programming (PPoPP)*'
doi: 10.1145/1229428.1229441
---
