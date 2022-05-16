---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'TAPE: A Transactional Application Profiling Environment'
subtitle: ''
summary: ''
authors:
- Hassan Chafi
- Chi Cao Minh
- Austen McDonald
- Brian D. Carlstrom
- JaeWoong Chung
- Lance Hammond
- admin
- Kunle Olukotun
tags: []
categories: []
date: '2005-06-01'
lastmod: 2022-05-15T13:35:24-07:00
featured: false
draft: false
venue: ICS'05

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
publishDate: '2022-05-15T20:35:24.364979Z'
publication_types:
- '1'
abstract: Transactional Coherence and Consistency (TCC) provides a new parallel programming
  model that uses transactions as the basic unit of parallel work and communication.
  TCC simplifies the development of correct parallel code because hardware provides
  transaction atomicity and ordering. Nevertheless, the programmer or a dynamic compiler
  must still optimize the parallel code for performance.This paper presents TAPE,
  a hardware and software infrastructure for profiling in TCC systems. TAPE extends
  the hardware for transactional execution to identify performance impediments such
  as dependence violations, buffer overflows, and work imbalance. It filters infrequent
  events to reduce resource requirements and allows the programmer to focus on the
  most important bottlenecks. We demonstrate that TAPE introduces minimal die area
  and performance overhead and can be used continuously, even for production runs.
  Moreover, we demonstrate how to leverage the profiling information to guide optimization
  for a set of parallel applications. TAPE accurately identifies the source code location
  and type of the most important bottlenecks, allowing a programmer to achieve maximum
  parallel speedup with a few profiling steps.
publication: '*Proceedings of the 19th International Conference on Supercomputing
  (ICS)*'
doi: 10.1145/1088149.1088176
---
