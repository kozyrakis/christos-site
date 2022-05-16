---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Pipelined multi-queue management in a VLSI ATM switch chip with credit-based
  flow-control
subtitle: ''
summary: ''
authors:
- G. Kornaros
- admin
- P. Vatsolaki
- M. Katevenis
tags:
- Switches;Very large scale integration;Asynchronous transfer mode;Pipelines;Clocks;Logic;Aggregates;Throughput;Delay;Monitoring
categories: []
date: '1997-09-01'
lastmod: 2022-05-15T13:35:26-07:00
featured: false
draft: false
venue: ARVLSI'97

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
publishDate: '2022-05-15T20:35:25.998744Z'
publication_types:
- '1'
abstract: We describe the queue management block of ATLAS I, a single-chip ATM switch
  (roster) with optional credit-based (backpressure) flow control. ATLAS I is a 4-million-transistor
  0.35-micron CMOS chip, currently under development, offering 20 Gbit/s aggregate
  I/O throughput, sub-microsecond cut-through latency, 256-cell shared buffer containing
  multiple logical output queues, priorities, multicasting, and load monitoring. The
  queue management block of ATLAS I is a dual parallel pipeline that manages the multiple
  queues of ready cells, the per-flow-group credits, and the cells that are waiting
  for credits. All cells, in all queues, share one, common buffer space. These 3-
  and Q-stage pipelines handle events at the rate of one cell arrival or departure
  per clock cycle, and one credit arrival per clock cycle. The queue management block
  consists of two compiled SRAMs, pipeline bypass logic, and multi-port CAM and SRAM
  blocks that are laid out in full-custom and support special access operations. The
  full-custom part of queue management contains approximately 65 thousand transistors
  in logic and 14 Kbits in various special memories, it occupies 2.3 mm/sup 2/, it
  consumes 270 mW (worst case), and it operates at 80 MHz (worst case) versus 50 MHz
  which is the required clock frequency to support the 622 Mb/s switch link rate.
publication: '*Proceedings of the 17th Conference on Advanced Research in VLSI (ARVLSI)*'
doi: 10.1109/ARVLSI.1997.634851
---
