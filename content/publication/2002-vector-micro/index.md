---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Vector vs. superscalar and VLIW architectures for embedded multimedia benchmarks
subtitle: ''
summary: ''
authors:
- admin
- David Patterson
tags:
- VLIW;Energy consumption;Prototypes;Vector processors;Reduced instruction set computing;Clocks;Frequency;Manuals;Design
  optimization;Digital signal processing chips
categories: []
date: '2002-11-01'
lastmod: 2022-05-15T13:35:25-07:00
featured: false
draft: false
venue: MICRO'02

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
publishDate: '2022-05-15T20:35:25.190174Z'
publication_types:
- '1'
abstract: Multimedia processing on embedded devices requires an architecture that
  leads to high performance, low power consumption, reduced design complexity, and
  small code size. In this paper, we use EEMBC, an industrial benchmark suite, to
  compare the VIRAM vector architecture to superscalar and VLIW processors for embedded
  multimedia applications. The comparison covers the VIRAM instruction set, vectorizing
  compiler and the prototype chip that integrates a vector processor with DRAM main
  memory. We demonstrate that executable code for VIRAM is up to 10 times smaller
  than VLIW code and comparable to /spl times/86 CISC code. The simple, cache-less
  VIRAM chip is 2 times faster than a 4-way superscalar RISC processor that uses a
  5 times faster clock frequency and consumes 10 times more power VIRAM is also 10
  times faster than cache-based VLIW processors. Even after manual optimization of
  the VLIW code and insertion of SIMD and DSP instructions, the single-issue VIRAM
  processor is 60% faster than 5-way to 8-way VLIW designs.
publication: '*Proceedings of the 35th IEEE/ACM International Symposium on Microarchitecture
  (MICRO)*'
doi: 10.1109/MICRO.2002.1176257
---
