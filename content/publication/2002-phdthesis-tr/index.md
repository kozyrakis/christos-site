---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Scalable Vector Media Processors for Embedded Systems
subtitle: ''
summary: ''
authors:
- admin
tags:
- intelligent memory
- vector processors
- multimedia
- energy efficiency},
categories: []
date: '2002-05-01'
lastmod: 2022-05-15T13:35:25-07:00
featured: false
draft: false
venue: PhD Thesis

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
abstract: Over the past twenty years, processor designers have concentrated on 
  superscalar and VLIW architectures that exploit the instruction-level parallelism
  (ILP) available in engineering applications for workstation systems. Recently,
  however, the focus in computing has shifted from engineering to multimedia
  applications and from workstations to embedded systems. In this new computing
  environment, the performance, energy consumption, and development cost of ILP
  processors renders them ineffective despite their theoretical generality. This
  thesis focuses on the development of efficient architectures for embedded multimedia
  systems. We argue that it is possible to design processors that deliver high
  performance, have low energy consumption, and are simple to implement. The basis for
  the argument is the ability of vector architectures to exploit efficiently the
   data-level parallelism in multimedia applications. Furthermore, the increasing 
   density of CMOS chips enables the design of cost-effective, on-chip, memory systems 
   that can support the high bandwidth necessary for a vector processor. To test our 
   hypothesis, we present VIRAM, a vector architecture for multimedia processing. We 
   demonstrate that the vector instructions in VIRAM can capture the data-level 
   parallelism in multimedia tasks and lead to smaller code size than RISC, CISC, and 
   VLIW architectures. We also describe two scalable microarchitectures 
   for vector media-processors (VIRAM-1 and CODE).
   VIRAM-1 integrates a simple, yet highly parallel, vector processor with an embedded DRAM memory system in a prototype chip with 120 million transistors. CODE uses a composite and decoupled
   organization for the vector processor in order to simplify the vector register file design, tolerate high
   memory latency, and allow for precise exceptions support. Both microarchitectures provide up to 10 times higher performance than alternative approaches without using out-of-order or wide instruction issue techniques that exacerbate energy consumption and design complexity. 
publication: 'University of California at Berkeley UCB-CSD-02-1183'
---
