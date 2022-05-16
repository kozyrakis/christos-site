---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The OpenTM Transactional Application Programming Interface
subtitle: ''
summary: ''
authors:
- Woongki Baek
- Chi Cao Minh
- Martin Trautmann
- admin
- Kunle Olukotun
tags: []
categories: []
date: '2007-09-01'
lastmod: 2022-05-15T13:35:21-07:00
featured: false
draft: false
venue: PACT'07

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
publishDate: '2022-05-15T20:35:21.076258Z'
publication_types:
- '1'
abstract: Transactional Memory (TM) simplifies parallel programming by supporting
  atomic and isolated execution of user-identified tasks. To date, TM programming
  has required the use of libraries that make it difficult to achieve scalable performance
  with code that is easy to develop and maintain. For TM programming to become practical,
  it is important to integrate TM into familiar, high-level environments for parallel
  programming. This paper presents OpenTM, an application programming interface (API)
  for parallel programming with transactions. OpenTM extends OpenMP, a widely used
  API for shared-memory parallel programming, with a set of compiler directives to
  express non-blocking synchronization and speculative parallelization based on memory
  transactions. We also present a portable OpenTM implementation that produces code
  for hardware, software, and hybrid TM systems. The implementation builds upon the
  OpenMP support in the GCC compiler and includes a runtime for the C programming
  language. We evaluate the performance and programmability features of OpenTM. We
  show that it delivers the performance of fine-grain locks at the programming simplicity
  of coarsegrain locks. Compared to transactional programming with lower-level interfaces,
  it removes the burden of manual annotations for accesses to shared variables and
  enables easy changes of the scheduling and contention management policies. Overall,
  OpenTM provides a practical and efficient TM programming environment within the
  familiar scope of OpenMP.
publication: '*Proceedings of the 16th International Conference on Parallel Architecture
  and Compilation Techniques (PACT)*'
---
