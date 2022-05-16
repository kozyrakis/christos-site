---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'GhOSt: Fast &amp; Flexible User-Space Delegation of Linux Scheduling'
subtitle: ''
summary: ''
authors:
- Jack Tigar Humphries
- Neel Natu
- Ashwin Chaugule
- Ofir Weisse
- Barret Rhoden
- Josh Don
- Luigi Rizzo
- Oleg Rombakh
- Paul Turner
- admin
tags:
- Operating systems
- thread scheduling
categories: []
date: '2021-10-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue: SOSP'21

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
publishDate: '2022-05-15T20:35:09.690732Z'
publication_types:
- '1'
abstract: We present ghOSt, our infrastructure for delegating kernel scheduling decisions
  to userspace code. ghOSt is designed to support the rapidly evolving needs of our
  data center workloads and platforms.Improving scheduling decisions can drastically
  improve the throughput, tail latency, scalability, and security of important workloads.
  However, kernel schedulers are difficult to implement, test, and deploy efficiently
  across a large fleet. Recent research suggests bespoke scheduling policies, within
  custom data plane operating systems, can provide compelling performance results
  in a data center setting. However, these gains have proved difficult to realize
  as it is impractical to deploy a custom OS image(s) at an application granularity,
  particularly in a multi-tenant environment, limiting the practical applications
  of these new techniques.ghOSt provides general-purpose delegation of scheduling
  policies to userspace processes in a Linux environment. ghOSt provides state encapsulation,
  communication, and action mechanisms that allow complex expression of scheduling
  policies within a userspace agent, while assisting in synchronization. Programmers
  use any language to develop and optimize policies, which are modified without a
  host reboot. ghOSt supports a wide range of scheduling models, from per-CPU to centralized,
  run-to-completion to preemptive, and incurs low overheads for scheduling actions.
  We demonstrate ghOSt's performance on both academic and real-world workloads, including
  Google Snap and Google Search. We show that by using ghOSt instead of the kernel
  scheduler, we can quickly achieve comparable throughput and latency while enabling
  policy optimization, non-disruptive upgrades, and fault isolation for our data center
  workloads. We open-source our implementation to enable future research and development
  based on ghOSt.
publication: '*Proceedings of the ACM SIGOPS 28th Symposium on Operating Systems Principles
  (SOSP)*'
doi: 10.1145/3477132.3483542
---
