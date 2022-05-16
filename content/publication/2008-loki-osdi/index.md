---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Hardware Enforcement of Application Security Policies Using Tagged Memory
subtitle: ''
summary: ''
authors:
- Nickolai Zeldovich
- Hari Kannan
- Michael Dalton
- admin
tags: []
categories: []
date: '2008-12-01'
lastmod: 2022-05-15T13:35:20-07:00
featured: false
draft: false
venue: OSDI'08

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
publishDate: '2022-05-15T20:35:20.012578Z'
publication_types:
- '1'
abstract: Computers are notoriously insecure, in part because application security
  policies do not map well onto traditional protection mechanisms such as Unix user
  accounts or hardware page tables. Recent work has shown that application policies
  can be expressed in terms of information flow restrictions and enforced in an OS
  kernel, providing a strong assurance of security. This paper shows that enforcement
  of these policies can be pushed largely into the processor itself, by using tagged
  memory support, which can provide stronger security guarantees by enforcing application
  security even if the OS kernel is compromised.We present the Loki tagged memory
  architecture, along with a novel operating system structure that takes advantage
  of tagged memory to enforce application security policies in hardware. We built
  a full-system prototype of Loki by modifying a synthesizable SPARC core, mapping
  it to an FPGA board, and porting HiStar, a Unix-like operating system, to run on
  it. One result is that Loki allows HiStar, an OS already designed to have a small
  trusted kernel, to further reduce the amount of trusted code by a factor of two,
  and to enforce security despite kernel compromises. Using various workloads, we
  also demonstrate that HiStar running on Loki incurs a low performance overhead.
publication: '*Proceedings of the 8th USENIX Conference on Operating Systems Design
  and Implementation (OSDI)*'
---
