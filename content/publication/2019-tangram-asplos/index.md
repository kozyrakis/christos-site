---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'TANGRAM: Optimized Coarse-Grained Dataflow for Scalable NN Accelerators'
subtitle: ''
summary: ''
authors:
- Mingyu Gao
- Xuan Yang
- Jing Pu
- Mark Horowitz
- admin
tags:
- dataflow
- parallelism
- neural networks
categories: []
date: '2019-04-01'
lastmod: 2022-05-15T13:35:11-07:00
featured: false
draft: false
venue: ASPLOS'19

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
publishDate: '2022-05-15T20:35:11.476184Z'
publication_types:
- '1'
abstract: 'The use of increasingly larger and more complex neural networks (NNs) makes
  it critical to scale the capabilities and efficiency of NN accelerators. Tiled architectures
  provide an intuitive scaling solution that supports both coarse-grained parallelism
  in NNs: intra-layer parallelism, where all tiles process a single layer, and inter-layer
  pipelining, where multiple layers execute across tiles in a pipelined manner. This
  work proposes dataflow optimizations to address the shortcomings of existing parallel
  dataflow techniques for tiled NN accelerators. For intra-layer parallelism, we develop
  buffer sharing dataflow that turns the distributed buffers into an idealized shared
  buffer, eliminating excessive data duplication and the memory access overheads.
  For inter-layer pipelining, we develop alternate layer loop ordering that forwards
  the intermediate data in a more fine-grained and timely manner, reducing the buffer
  requirements and pipeline delays. We also make inter-layer pipelining applicable
  to NNs with complex DAG structures. These optimizations improve the performance
  of tiled NN accelerators by 2x and reduce their energy consumption by 45% across
  a wide range of NNs. The effectiveness of our optimizations also increases with
  the NN size and complexity.'
publication: '*Proceedings of the 24th International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/3297858.3304014
---
