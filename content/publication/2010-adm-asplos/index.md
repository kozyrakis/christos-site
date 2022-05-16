---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Flexible Architectural Support for Fine-Grain Scheduling
subtitle: ''
summary: ''
authors:
- Daniel Sanchez
- Richard M. Yoo
- admin
tags:
- many-core
- scheduling
- fine-grain scheduling
- messaging
- work-stealing
- chip-multiprocessors
categories: []
date: '2010-03-01'
lastmod: 2022-05-15T13:35:19-07:00
featured: false
draft: false
venue: ASPLOS'10

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
publishDate: '2022-05-15T20:35:19.018653Z'
publication_types:
- '1'
abstract: To make efficient use of CMPs with tens to hundreds of cores, it is often
  necessary to exploit fine-grain parallelism. However, managing tasks of a few thousand
  instructions is particularly challenging, as the runtime must ensure load balance
  without compromising locality and introducing small overheads. Software-only schedulers
  can implement various scheduling algorithms that match the characteristics of different
  applications and programming models, but suffer significant overheads as they synchronize
  and communicate task information over the deep cache hierarchy of a large-scale
  CMP. To reduce these costs, hardware-only schedulers like Carbon, which implement
  task queuing and scheduling in hardware, have been proposed. However, a hardware-only
  solution fixes the scheduling algorithm and leaves no room for other uses of the
  custom hardware.This paper presents a combined hardware-software approach to build
  fine-grain schedulers that retain the flexibility of software schedulers while being
  as fast and scalable as hardware ones. We propose asynchronous direct messages (ADM),
  a simple architectural extension that provides direct exchange of asynchronous,
  short messages between threads in the CMP without going through the memory hierarchy.
  ADM is sufficient to implement a family of novel, software-mostly schedulers that
  rely on low-overhead messaging to efficiently coordinate scheduling and transfer
  task information. These schedulers match and often exceed the performance and scalability
  of Carbon when using the same scheduling algorithm. When the ADM runtime tailors
  its scheduling algorithm to application characteristics, it outperforms Carbon by
  up to 70%.
publication: '*Proceedings of the 15th International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/1736020.1736055
---
