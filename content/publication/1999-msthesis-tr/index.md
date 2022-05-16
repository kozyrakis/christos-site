---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Media-Enhanced Vector Architecture for Embedded Memory Systems
subtitle: ''
summary: ''
authors:
- admin
tags:
- intelligent memory
- energy efficiency
- DRAM vector processor
- SIMD
- multimedia
categories: []
date: '1999-07-01'
lastmod: 2022-05-15T13:35:25-07:00
featured: false
draft: false
venue: MS Thesis

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
publishDate: '2022-05-15T20:35:25.674026Z'
publication_types:
- '7'
abstract: Next generation portable devices will require processors with both low energy
  consumption and high performance for media functions. At the same time, modern CMOS
  technology creates the need for highly scalable VLSI architectures. Conventional
  processor architectures fail to meet these requirements. This paper presents the
  architecture of Vector IRAM (VIRAM), a processor that combines vector processing
  with embedded DRAM technology. Vector processing achieves high multimedia performance
  with simple hardware, while embedded DRAM provides high memory bandwidth at low
  energy consumption. VIRAM provides flexible support for media data types, short
  vectors, and DSP features. The vector pipeline is enhanced to hide DRAM latency
  without using caches. The peak performance is 3.2 GFLOPS (single precision) and
  maximum memory bandwidth is 25.6 GBytes/s. With a target power consumption of 2
  Watts for the vector pipeline and the memory system, VIRAM supports 1.6 GFLOPS/Watt.
  For a set of representative media kernels, VIRAM sustains on average 88% of its
  peak performance, outperforming conventional SIMD media extensions and DSP processors
  by factors of 4.5 to 17. Using a clustered implementation approach, the modular
  design can be scaled without complicating control logic. We demonstrate that scaling
  the architecture leads to near linear application speedup. We also evaluate the
  effect of scaling the capacity and parallelism of the on-chip memory system to die
  area and sustained performance.
publication: 'University of California at Berkeley UCB-CSD-99-1059'
---
