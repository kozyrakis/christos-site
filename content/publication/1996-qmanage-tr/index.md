---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The Architecture, Operation, and Design of the Queue Management Block in the
  ATLAS I ATM Switch
subtitle: ''
summary: ''
authors:
- admin
tags:
- VLSI switches
- ATM switches
- ATLAS I switch
- shared buffer
- credit-based flow-control
- multiple output queues
- queue management
- pipelining
- priority enforcer
categories: []
date: '1996-07-01'
lastmod: 2022-05-15T13:35:26-07:00
featured: false
venue: BS Thesis

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
publishDate: '2022-05-15T20:35:26.411947Z'
publication_types:
- '4'
abstract: Among the various switch buffer architectures, output queueing implemented
  in a completely shared buffer is the one that achieves the highest possible utilization
  of both output bandwidth and buffer space. The high link throughput, small cell
  size and additional features of ATM switching, such as multiple classes of service,
  multicasting and flow control, enforce further extensions to the above scheme and
  demand pure hardware implementations. In this work we present the hardware block
  maintaining output queues per priority class in the ATLAS I single chip ATM switch.
  It also provides support for multicasting and multi-lane credit-based flow control.
  Techniques such as pipelined and superscalar processing, usually employed in processors’
  design, are used in order to accommodate for the amount and high speed of operation
  required. This also modifies the approach to the timing of operations, the control
  design and the calculation of the hardware complexity. The block was extensively
  simulated to ensure the correctness of its operation. Although the hardware implementation
  is currently in progress, the circuits already laid out are presented, while the
  VLSI design of the remaining blocks is analyzed. In addition, the Priority Enforcer
  circuit and its full-custom layout is thoroughly described.
publication: 'ICS/FORTH Technical Report TR-172'
---
