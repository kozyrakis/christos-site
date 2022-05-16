---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SmartHarvest: Harvesting Idle CPUs Safely and Efficiently in the Cloud'
subtitle: ''
summary: ''
authors:
- Yawen Wang
- Kapil Arya
- Marios Kogias
- Manohar Vanga
- Aditya Bhandari
- Neeraja J. Yadwadkar
- Siddhartha Sen
- Sameh Elnikety
- admin
- Ricardo Bianchini
tags: []
categories: []
date: '2021-04-01'
lastmod: 2022-05-15T13:35:10-07:00
featured: false
draft: false
venue: EuroSys'21

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
publishDate: '2022-05-15T20:35:09.936972Z'
publication_types:
- '1'
abstract: We can increase the efficiency of public cloud datacenters by harvesting
  allocated but temporarily idling CPU cores from customer virtual machines (VMs)
  to run batch or analytics workloads. Even small efficiency gains translate into
  substantial savings, since provisioning and operating a datacenter costs hundreds
  of millions of dollars per year. The main challenge is to harvest idle cores with
  little or no impact on customer VMs, which could be running latency-sensitive services
  and are essentially black-boxes to the cloud provider.We introduce ElasticVM, a
  new VM type that can run batch workloads cheaply using mainly harvested cores. We
  also propose SmartHarvest, a system that dynamically manages the number of cores
  available to ElasticVMs in each fine-grained time window. SmartHarvest uses online
  learning to predict the core demand of primary, customer VMs and compute the number
  of cores that can be safely harvested. Our results show that SmartHarvest can harvest
  a significant amount of CPU resources without increasing the 99th-percentile tail
  latency of latency-critical primary workloads by more than 10%. Unlike static harvesting
  techniques that rely on offline profiling, SmartHarvest is robust to different primary
  workloads, batch workloads, and load changes. Finally, we show that the online learning
  in SmartHarvest is complementary to systems optimizations for VM management.
publication: '*Proceedings of the 16th European Conference on Computer Systems (EuroSys)*'
doi: 10.1145/3447786.3456225
---
