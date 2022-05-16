---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Low Power Front-End for Embedded Processors Using a Block-Aware Instruction
  Set
subtitle: ''
summary: ''
authors:
- Ahmad Zmily
- admin
tags:
- low power front-end
- instruction re-ordering
- unified instruction cache and BTB
- tagless instruction cache
- software hints
- instruction prefetching
categories: []
date: '2007-09-01'
lastmod: 2022-05-15T13:35:21-07:00
featured: false
draft: false
venue: CASES'07

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
publishDate: '2022-05-15T20:35:20.993690Z'
publication_types:
- '1'
abstract: Energy, power, and area efficiency are critical design concerns for embedded
  processors. Much of the energy of a typical embedded processor is consumed in the
  front-end since instruction fetching happens on nearly every cycle and involves
  accesses to large memory arrays such as instruction and branch target caches. The
  use of small front-end arrays leads to significant power and area savings, but typically
  results in significant performance degradation. This paper evaluates and compares
  optimizations that improve the performance of embedded processors with small front-end
  caches. We examine both software techniques, such as instruction re-ordering and
  selective caching, and hardware techniques, such as instruction prefetching, tagless
  instruction cache, and unified caches for instruction and branch targets. We demonstrate
  that, building on top of a block-aware instruction set, these optimizations can
  eliminate the performance degradation due to small front-end caches. Moreover, selective
  combinations of these optimizations lead to an embedded processor that performs
  significantly better than the large cache design while maintaining the area and
  energy efficiency of the small cache design.
publication: '*Proceedings of the 2007 International Conference on Compilers, Architecture,
  and Synthesis for Embedded Systems (CASES)*'
doi: 10.1145/1289881.1289926
---
