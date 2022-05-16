---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Executing Java Programs with Transactional Memory
subtitle: ''
summary: ''
authors:
- Brian D. Carlstrom
- JaeWoong Chung
- Hassan Chafi
- Austen McDonald
- Chi Cao Minh
- Lance Hammond
- admin
- Kunle Olukotun
tags:
- transactions
- multiprocessor architecture
- feedback optimization
categories: []
date: '2006-12-01'
lastmod: 2022-05-15T13:35:22-07:00
featured: false
draft: false
venue: SCP

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
publishDate: '2022-05-15T20:35:22.394402Z'
publication_types:
- '2'
abstract: Parallel programming is difficult due to the complexity of dealing with
  conventional lock-based synchronization. To simplify parallel programming, there
  have been a number of proposals to support transactions directly in hardware and
  eliminate locks completely. Although hardware support for transactions has the potential
  to completely change the way parallel programs are written, initially transactions
  will be used to execute existing parallel programs. In this paper we investigate
  the implications of using transactions to execute existing parallel Java programs.
  Our results show that transactions can be used to support all aspects of Java multithreaded
  programs, and once Java virtual machine issues have been addressed, the conversion
  of a lock-based application into transactions is largely straightforward. The performance
  that these converted applications achieve is equal to or sometimes better than the
  original lock-based implementation.
publication: '*Science of Computer Programming*'
doi: 10.1016/j.scico.2006.05.006
---
