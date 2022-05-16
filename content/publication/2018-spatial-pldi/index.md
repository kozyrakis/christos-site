---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Spatial: A Language and Compiler for Application Accelerators'
subtitle: ''
summary: ''
authors:
- David Koeplinger
- Matthew Feldman
- Raghu Prabhakar
- Yaqi Zhang
- Stefan Hadjis
- Ruben Fiszel
- Tian Zhao
- Luigi Nardi
- Ardavan Pedram
- admin
- Kunle Olukotun
tags:
- compilers
- reconfigurable architectures
- CGRAs
- hardware accelerators
- high-level synthesis
- domain-specific languages
- FPGAs
categories: []
date: '2018-06-01'
lastmod: 2022-05-15T13:35:12-07:00
featured: false
draft: false
venue: PLDI'18

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
publishDate: '2022-05-15T20:35:12.292822Z'
publication_types:
- '1'
abstract: Industry is increasingly turning to reconfigurable architectures like FPGAs
  and CGRAs for improved performance and energy efficiency. Unfortunately, adoption
  of these architectures has been limited by their programming models. HDLs lack abstractions
  for productivity and are difficult to target from higher level languages. HLS tools
  are more productive, but offer an ad-hoc mix of software and hardware abstractions
  which make performance optimizations difficult.  In this work, we describe a new
  domain-specific language and compiler called Spatial for higher level descriptions
  of application accelerators. We describe Spatial's hardware-centric abstractions
  for both programmer productivity and design performance, and summarize the compiler
  passes required to support these abstractions, including pipeline scheduling, automatic
  memory banking, and automated design tuning driven by active machine learning. We
  demonstrate the language's ability to target FPGAs and CGRAs from common source
  code. We show that applications written in Spatial are, on average, 42% shorter
  and achieve a mean speedup of 2.9x over SDAccel HLS when targeting a Xilinx UltraScale+
  VU9P FPGA on an Amazon EC2 F1 instance.
publication: '*Proceedings of the 39th ACM SIGPLAN Conference on Programming Language
  Design and Implementation (PLDI)*'
doi: 10.1145/3192366.3192379
---
