---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Automatic Generation of Efficient Accelerators for Reconfigurable Hardware
subtitle: ''
summary: ''
authors:
- David Koeplinger
- Raghu Prabhakar
- Yaqi Zhang
- Christina Delimitrou
- admin
- Kunle Olukotun
tags: []
categories: []
date: '2016-06-01'
lastmod: 2022-05-15T13:35:13-07:00
featured: false
draft: false
venue: ISCA'16

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
publishDate: '2022-05-15T20:35:13.768694Z'
publication_types:
- '1'
abstract: Acceleration in the form of customized datapaths offer large performance
  and energy improvements over general purpose processors. Reconfigurable fabrics
  such as FPGAs are gaining popularity for use in implementing application-specific
  accelerators, thereby increasing the importance of having good high-level FPGA design
  tools. However, current tools for targeting FPGAs offer inadequate support for high-level
  programming, resource estimation, and rapid and automatic design space exploration.We
  describe a design framework that addresses these challenges. We introduce a new
  representation of hardware using parameterized templates that captures locality
  and parallelism information at multiple levels of nesting. This representation is
  designed to be automatically generated from high-level languages based on parallel
  patterns. We describe a hybrid area estimation technique which uses template-level
  models and design-level artificial neural networks to account for effects from hardware
  place-and-route tools, including routing overheads, register and block RAM duplication,
  and LUT packing. Our runtime estimation accounts for off-chip memory accesses. We
  use our estimation capabilities to rapidly explore a large space of designs across
  tile sizes, parallelization factors, and optional coarse-grained pipelining, all
  at multiple loop levels. We show that estimates average 4.8% error for logic resources,
  6.1% error for runtimes, and are 279 to 6533 times faster than a commercial high-level
  synthesis tool. We compare the best-performing designs to optimized CPU code running
  on a server-grade 6 core processor and show speedups of up to 16.7×.
publication: '*Proceedings of the 43rd International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1109/ISCA.2016.20
---
