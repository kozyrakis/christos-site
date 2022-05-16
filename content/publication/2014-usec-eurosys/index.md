---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Reconciling High Server Utilization and Sub-Millisecond Quality-of-Service
subtitle: ''
summary: ''
authors:
- Jacob Leverich
- admin
tags: []
categories: []
date: '2014-04-01'
lastmod: 2022-05-15T13:35:15-07:00
featured: false
draft: false
venue: EuroSys'14

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
publishDate: '2022-05-15T20:35:15.319781Z'
publication_types:
- '1'
abstract: The simplest strategy to guarantee good quality of service (QoS) for a latency-sensitive
  workload with sub-millisecond latency in a shared cluster environment is to never
  run other workloads concurrently with it on the same server. Unfortunately, this
  inevitably leads to low server utilization, reducing both the capability and cost
  effectiveness of the cluster.In this paper, we analyze the challenges of maintaining
  high QoS for low-latency workloads when sharing servers with other workloads. We
  show that workload co-location leads to QoS violations due to increases in queuing
  delay, scheduling delay, and thread load imbalance. We present techniques that address
  these vulnerabilities, ranging from provisioning the latency-critical service in
  an interference aware manner, to replacing the Linux CFS scheduler with a scheduler
  that provides good latency guarantees and fairness for co-located workloads. Ultimately,
  we demonstrate that some latency-critical workloads can be aggressively co-located
  with other workloads, achieve good QoS, and that such co-location can improve a
  datacenter's effective throughput per TCO-$ by up to 52%.
publication: '*Proceedings of the 9th European Conference on Computer Systems (EuroSys)*'
doi: 10.1145/2592798.2592821
---
