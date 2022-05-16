---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'ATLAS: A Chip-Multiprocessor with Transactional Memory Support'
subtitle: ''
summary: ''
authors:
- Njuguna Njoroge
- Jared Casper
- Sewook Wee
- Yuriy Teslyar
- Daxia Ge
- admin
- Kunle Olukotun
tags: []
categories: []
date: '2007-01-01'
lastmod: 2022-05-15T13:35:21-07:00
featured: false
draft: false
venue: DATE'07

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
publishDate: '2022-05-15T20:35:21.733752Z'
publication_types:
- '1'
abstract: Chip-multiprocessors are quickly becoming popular in embedded systems. However,
  the practical success of CMPs strongly depends on addressing the difficulty of multithreaded
  application development for such systems. Transactional Memory (TM) promises to
  simplify concurrency management in multithreaded applications by allowing programmers
  to specify coarse-grain parallel tasks, while achieving performance comparable to
  fine-grain lock-based applications.This paper presents ATLAS, the first prototype
  of a CMP with hardware support for transactional memory. ATLAS includes 8 embedded
  PowerPC cores that access coherent shared memory in a transactional manner. The
  data cache for each core is modified to support the speculative buffering and conflict
  detection necessary for transactional execution. We have mapped ATLAS to the BEE2
  multi-FPGA board to create a full-system prototype that operates at 100MHz, boots
  Linux, and provides significant performance and ease-of-use benefits for a range
  of parallel applications. Overall, the ATLAS prototype provides an excellent framework
  for further research on the software and hardware techniques necessary to deliver
  on the potential of transactional memory.
publication: '*Proceedings of the Conference on Design, Automation and Test in Europe
  (DATE)*'
---
