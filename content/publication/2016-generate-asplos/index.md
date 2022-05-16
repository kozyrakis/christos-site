---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Generating Configurable Hardware from Parallel Patterns
subtitle: ''
summary: ''
authors:
- Raghu Prabhakar
- David Koeplinger
- Kevin J. Brown
- HyoukJoong Lee
- Christopher De Sa
- admin
- Kunle Olukotun
tags:
- reconfigurable hardware
- metapipelining
- parallel patterns
- hardware generation
- tiling
- FPGAs
categories: []
date: '2016-04-01'
lastmod: 2022-05-15T13:35:14-07:00
featured: false
draft: false
venue: ASPLOS'16

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
publishDate: '2022-05-15T20:35:14.178545Z'
publication_types:
- '1'
abstract: 'In recent years the computing landscape has seen an increasing shift towards
  specialized accelerators. Field programmable gate arrays (FPGAs) are particularly
  promising for the implementation of these accelerators, as they offer significant
  performance and energy improvements over CPUs for a wide class of applications and
  are far more flexible than fixed-function ASICs. However, FPGAs are difficult to
  program. Traditional programming models for reconfigurable logic use low-level hardware
  description languages like Verilog and VHDL, which have none of the productivity
  features of modern software languages but produce very efficient designs, and low-level
  software languages like C and OpenCL coupled with high-level synthesis (HLS) tools
  that typically produce designs that are far less efficient. Functional languages
  with parallel patterns are a better fit for hardware generation because they provide
  high-level abstractions to programmers with little experience in hardware design
  and avoid many of the problems faced when generating hardware from imperative languages.
  In this paper, we identify two important optimizations for using parallel patterns
  to generate efficient hardware: tiling and metapipelining. We present a general
  representation of tiled parallel patterns, and provide rules for automatically tiling
  patterns and generating metapipelines. We demonstrate experimentally that these
  optimizations result in speedups up to 39.4× on a set of benchmarks from the data
  analytics domain.'
publication: '*Proceedings of the 21st International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/2872362.2872415
---
