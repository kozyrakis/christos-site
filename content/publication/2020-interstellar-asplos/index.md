---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Interstellar: Using Halide's Scheduling Language to Analyze DNN Accelerators"
subtitle: ''
summary: ''
authors:
- Xuan Yang
- Mingyu Gao
- Qiaoyi Liu
- Jeff Setter
- Jing Pu
- Ankita Nayak
- Steven Bell
- Kaidi Cao
- Heonjae Ha
- Priyanka Raina
- admin
- Mark Horowitz
tags: []
categories: []
date: '2020-03-01'
lastmod: 2022-05-15T13:35:10-07:00
featured: false
draft: false
venue: ASPLOS'20

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
publishDate: '2022-05-15T20:35:10.665940Z'
publication_types:
- '1'
abstract: We show that DNN accelerator micro-architectures and their program mappings
  represent specific choices of loop order and hardware parallelism for computing
  the seven nested loops of DNNs, which enables us to create a formal taxonomy of
  all existing dense DNN accelerators. Surprisingly, the loop transformations needed
  to create these hardware variants can be precisely and concisely represented by
  Halide's scheduling language. By modifying the Halide compiler to generate hardware,
  we create a system that can fairly compare these prior accelerators. As long as
  proper loop blocking schemes are used, and the hardware can support mapping replicated
  loops, many different hardware dataflows yield similar energy efficiency with good
  performance. This is because the loop blocking can ensure that most data references
  stay on-chip with good locality and the processing units have high resource utilization.
  How resources are allocated, especially in the memory system, has a large impact
  on energy and performance. By optimizing hardware resource allocation while keeping
  throughput constant, we achieve up to 4.2X energy improvement for Convolutional
  Neural Networks (CNNs), 1.6X and 1.8X improvement for Long Short-Term Memories (LSTMs)
  and multi-layer perceptrons (MLPs), respectively.
publication: '*Proceedings of the 25th International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
---
