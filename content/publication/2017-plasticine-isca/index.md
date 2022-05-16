---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Plasticine: A Reconfigurable Architecture For Parallel Paterns'
subtitle: ''
summary: ''
authors:
- Raghu Prabhakar
- Yaqi Zhang
- David Koeplinger
- Matt Feldman
- Tian Zhao
- Stefan Hadjis
- Ardavan Pedram
- admin
- Kunle Olukotun
tags:
- CGRAs
- reconfigurable architectures
- parallel patterns
- hardware accelerators
categories: []
date: '2017-01-01'
lastmod: 2022-05-15T13:35:13-07:00
featured: false
draft: false
venue: ISCA'17

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
publishDate: '2022-05-15T20:35:13.188830Z'
publication_types:
- '1'
abstract: Reconfigurable architectures have gained popularity in recent years as they
  allow the design of energy-efficient accelerators. Fine-grain fabrics (e.g. FPGAs)
  have traditionally suffered from performance and power inefficiencies due to bit-level
  reconfigurable abstractions. Both fine-grain and coarse-grain architectures (e.g.
  CGRAs) traditionally require low level programming and suffer from long compilation
  times. We address both challenges with Plasticine, a new spatially reconfigurable
  architecture designed to efficiently execute applications composed of parallel patterns.
  Parallel patterns have emerged from recent research on parallel programming as powerful,
  high-level abstractions that can elegantly capture data locality, memory access
  patterns, and parallelism across a wide range of dense and sparse applications.We
  motivate Plasticine by first observing key application characteristics captured
  by parallel patterns that are amenable to hardware acceleration, such as hierarchical
  parallelism, data locality, memory access patterns, and control flow. Based on these
  observations, we architect Plasticine as a collection of Pattern Compute Units and
  Pattern Memory Units. Pattern Compute Units are multi-stage pipelines of reconfigurable
  SIMD functional units that can efficiently execute nested patterns. Data locality
  is exploited in Pattern Memory Units using banked scratchpad memories and configurable
  address decoders. Multiple on-chip address generators and scatter-gather engines
  make efficient use of DRAM bandwidth by supporting a large number of outstanding
  memory requests, memory coalescing, and burst mode for dense accesses. Plasticine
  has an area footprint of 113 mm2 in a 28nm process, and consumes a maximum power
  of 49 W at a 1 GHz clock. Using a cycle-accurate simulator, we demonstrate that
  Plasticine provides an improvement of up to 76.9x in performance-per-Watt over a
  conventional FPGA over a wide range of dense and sparse applications.
publication: '*Proceedings of the 44th International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/3079856.3080256
---
