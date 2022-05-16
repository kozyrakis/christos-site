---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Transactional Programming in a Multi-Core Environment
subtitle: ''
summary: ''
authors:
- Ali-Reza Adl-Tabatabai
- admin
- Bratin Saha
tags:
- transactional memory
- atomicity
- parallel programming
- hardware architecture
categories: []
date: '2007-03-01'
lastmod: 2022-05-15T13:35:20-07:00
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
publishDate: '2022-05-15T20:35:20.828851Z'
publication_types:
- '1'
abstract: With single thread performance starting to plateau, HW architects have turned
  to chip level multiprocessing (CMP) to increase processing power. All major microprocessor
  companies are aggressively shipping multi-core products in the mainstream computing
  market. Moore's law will largely be used to increase HW thread-level parallelism
  through higher core counts in a CMP environment. CMPs bring new challenges into
  the design of the software system stack.In this tutorial, we talk about the shift
  to multi-core processors and the programming implications. In particular, we focus
  on transactional programming. Transactions have emerged as a promising alternative
  to lock-based synchronization that eliminates many of the problems associated with
  lock-based synchronization. We discuss the design of both hardware and software
  transactional memory and quantify the tradeoffs between the different design points.
  We show how to extend the Java and C languages with transactional constructs, and
  how to integrate transactions with compiler optimizations and the language runtime
  (e.g., memory manager and garbage collection).
publication: '*Proceedings of the 12th ACM SIGPLAN Symposium on Principles and Practice
  of Parallel Programming (PPoPP)*'
doi: 10.1145/1229428.1229484
---
