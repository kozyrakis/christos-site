---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Architectural Semantics for Practical Transactional Memory
subtitle: ''
summary: ''
authors:
- Austen McDonald
- JaeWoong Chung
- Brian D. Carlstrom
- Chi Cao Minh
- Hassan Chafi
- admin
- Kunle Olukotun
tags: []
categories: []
date: '2006-06-01'
lastmod: 2022-05-15T13:35:23-07:00
featured: false
draft: false
venue: ISCA'06

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
publishDate: '2022-05-15T20:35:22.974193Z'
publication_types:
- '1'
abstract: 'Transactional Memory (TM) simplifies parallel programming by allowing for
  parallel execution of atomic tasks. Thus far, TM systems have focused on implementing
  transactional state buffering and conflict resolution. Missing is a robust hardware/software
  interface, not limited to simplistic instructions defining transaction boundaries.
  Without rich semantics, current TM systems cannot support basic features of modern
  programming languages and operating systems such as transparent library calls, conditional
  synchronization, system calls, I/O, and runtime exceptions. This paper presents
  a comprehensive instruction set architecture (ISA) for TM systems. Our proposal
  introduces three key mechanisms: two-phase commit; support for software handlers
  on commit, violation, and abort; and full support for open- and closed-nested transactions
  with independent rollback. These mechanisms provide a flexible interface to implement
  programming language and operating system functionality. We also show that these
  mechanisms are practical to implement at the ISA and microarchitecture level for
  various TM systems. Using an execution-driven simulation, we demonstrate both the
  functionality (e.g., I/O and conditional scheduling within transactions) and performance
  potential (2.2× improvement for SPECjbb2000) of the proposed mechanisms. Overall,
  this paper establishes a rich and efficient interface to foster both hardware and
  software research on transactional memory.'
publication: '*Proceedings of the 33rd International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1109/ISCA.2006.9
---
