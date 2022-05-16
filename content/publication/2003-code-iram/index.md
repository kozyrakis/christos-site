---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Overcoming the limitations of conventional vector processors
subtitle: ''
summary: ''
authors:
- Christos Kozyrakis
- admin
tags:
- Vector processors;Registers;Delay;System-on-a-chip;Microarchitecture;Performance
  loss;Computer architecture;Bandwidth;CMOS technology;Computer science
categories: []
date: '2003-06-01'
lastmod: 2022-05-15T13:35:25-07:00
featured: false
draft: false
venue: ISCA'03

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
publishDate: '2022-05-15T20:35:25.104559Z'
publication_types:
- '1'
abstract: Despite their superior performance for multimedia applications, vector processors
  have three limitations that hinder their widespread acceptance. First, the complexity
  and size of the centralized vector register file limits the number of functional
  units. Second, precise exceptions for vector instructions are difficult to implement.
  Third, vector processors require an expensive on-chip memory system that supports
  high bandwidth at low access latency. We introduce CODE, a scalable vector microarchitecture
  that addresses these three shortcomings. It is designed around a clustered vector
  register file and uses a separate network for operand transfers across functional
  units. With extensive use of decoupling, it can hide the latency of communication
  across functional units and provides 26% performance improvement over a centralized
  organization. CODE scales efficiently to 8 functional units without requiring wide
  instruction issue capabilities. A renaming table makes the clustered register file
  transparent at the instruction set level. Renaming also enables precise exceptions
  for vector instructions at a performance loss of less than 5%. Finally, decoupling
  allows CODE to tolerate large increases in memory latency at sublinear performance
  degradation without using on-chip caches. Thus, CODE can use economical, off-chip,
  memory systems.
publication: '*Proceedings of the 30th International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1109/ISCA.2003.1207017
---
