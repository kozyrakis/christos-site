---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Scalable vector processors for embedded systems
subtitle: ''
summary: ''
authors:
- admin
- David Patterson
tags:
- Vector processors;Embedded system;Registers;VLIW;Computer architecture;Energy consumption;Embedded
  computing;Parallel processing;Process design;High performance computing
categories: []
date: '2003-11-01'
lastmod: 2022-05-15T13:35:25-07:00
featured: false
draft: false
venue: Top Picks'03

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
publishDate: '2022-05-15T20:35:25.023670Z'
publication_types:
- '2'
abstract: 'For embedded applications with data-level parallelism, a vector processor
  offers high performance at low power consumption and low design complexity. Unlike
  superscalar and VLIW designs, a vector processor is scalable and can optimally match
  specific application requirements.To demonstrate that vector architectures meet
  the requirements of embedded media processing, we evaluate the Vector IRAM, or VIRAM
  (pronounced \"V-IRAM\"), architecture developed at UC Berkeley, using benchmarks
  from the Embedded Microprocessor Benchmark Consortium (EEMBC). Our evaluation covers
  all three components of the VIRAM architecture: the instruction set, the vectorizing
  compiler, and the processor microarchitecture. We show that a compiler can vectorize
  embedded tasks automatically without compromising code density. We also describe
  a prototype vector processor that outperforms high-end superscalar and VLIW designs
  by 1.5x to 100x for media tasks, without compromising power consumption. Finally,
  we demonstrate that clustering and modular design techniques let a vector processor
  scale to tens of arithmetic data paths before wide instruction-issue capabilities
  become necessary.'
publication: '*IEEE Micro*'
doi: 10.1109/MM.2003.1261385
---
