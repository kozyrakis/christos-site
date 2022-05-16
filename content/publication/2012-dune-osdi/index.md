---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Dune: Safe User-Level Access to Privileged CPU Features'
subtitle: ''
summary: ''
authors:
- Adam Belay
- Andrea Bittau
- Ali Mashtizadeh
- David Terei
- David Mazières
- admin
tags: []
categories: []
date: '2012-10-01'
lastmod: 2022-05-15T13:35:16-07:00
featured: false
draft: false
venue: OSDI'12

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
publishDate: '2022-05-15T20:35:16.551138Z'
publication_types:
- '1'
abstract: 'Dune is a system that provides applications with direct but safe access
  to hardware features such as ring protection, page tables, and tagged TLBs, while
  preserving the existing OS interfaces for processes. Dune uses the virtualization
  hardware in modern processors to provide a process, rather than a machine abstraction.
  It consists of a small kernel module that initializes virtualization hardware and
  mediates interactions with the kernel, and a user-level library that helps applications
  manage privileged hardware features. We present the implementation of Dune for 64-
  bit x86 Linux. We use Dune to implement three user-level applications that can benefit
  from access to privileged hardware: a sandbox for untrusted code, a privilege separation
  facility, and a garbage collector. The use of Dune greatly simplifies the implementation
  of these applications and provides significant performance advantages.'
publication: '*Proceedings of the 10th USENIX Conference on Operating Systems Design
  and Implementatio (OSDI)*'
---
