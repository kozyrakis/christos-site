---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Hardware/compiler codevelopment for an embedded media processor
subtitle: ''
summary: ''
authors:
- admin
- D. Judd
- J. Gebis
- S. Williams
- D. Patterson
- K. Yelick
tags:
- Hardware;Multimedia systems;Microprocessors;Digital signal processors;Energy consumption;Power
  system modeling;Vector processors;Random access memory;Bandwidth;Prototypes
categories: []
date: '2001-11-01'
lastmod: 2022-05-15T13:35:25-07:00
featured: false
draft: false
venue: IEEE 

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
publishDate: '2022-05-15T20:35:25.270300Z'
publication_types:
- '2'
abstract: Embedded and portable systems running multimedia applications create a new
  challenge for hardware architects. A microprocessor for such applications needs
  to be easy to program like a general-purpose processor and have the performance
  and power efficiency of a digital signal processor. This paper presents the codevelopment
  of the instruction set, the hardware, and the compiler for the Vector IRAM media
  processor. A vector architecture is used to exploit the data parallelism of multimedia
  programs, which allows the use of highly modular hardware and enables implementations
  that combine high performance, low power consumption, and reduced design complexity.
  It also leads to a compiler model that is efficient both in terms of performance
  and executable code size. The memory system for the vector processor is implemented
  using embedded DRAM technology, which provides high bandwidth in an integrated,
  cost-effective manner. The hardware and the compiler for this architecture make
  complementary contributions to the efficiency of the overall system. This paper
  explores the interactions and tradeoffs between them, as well as the enhancements
  to a vector architecture necessary for multimedia processing. We also describe how
  the architecture, design, and compiler features come together in a prototype system-on-a-chip,
  able to execute 3.2 billion operations per second per watt.
publication: '*Proceedings of the IEEE*'
doi: 10.1109/5.964446
---
