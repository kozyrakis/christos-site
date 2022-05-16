---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Case against (Most) Context Switches
subtitle: ''
summary: ''
authors:
- Jack Tigar Humphries
- Kostis Kaffes
- David Mazières
- admin
tags: []
categories: []
date: '2021-06-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue: HotOS'21

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
publishDate: '2022-05-15T20:35:09.855468Z'
publication_types:
- '1'
abstract: Multiplexing software threads onto hardware threads and serving interrupts,
  VM-exits, and system calls require frequent context switches, causing high overheads
  and significant kernel and application complexity. We argue that context switching
  is an idea whose time has come and gone, and propose eliminating it through a radically
  different hardware threading model targeted to solve software rather than hardware
  problems. The new model adds a large number of hardware threads to each physical
  core - making thread multiplexing unnecessary - and lets software manage them. The
  only state change directly triggered in hardware by system calls, exceptions, and
  asynchronous hardware events will be blocking and unblocking hardware threads. We
  also present ISA extensions to allow kernel and user software to exploit this new
  threading model. Developers can use these extensions to eliminate interrupts and
  implement fast I/O without polling, exception-less system and hypervisor calls,
  practical microkernels, simple distributed programming models, and untrusted but
  fast hypervisors. Finally, we suggest practical hardware implementations and discuss
  the hardware and software challenges toward realizing this novel approach.
publication: '*Proceedings of the Workshop on Hot Topics in Operating Systems (HotOS)*'
doi: 10.1145/3458336.3465274
---
