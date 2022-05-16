---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Understanding Ephemeral Storage for Serverless Analytics
subtitle: ''
summary: ''
authors:
- Ana Klimovic
- Yawen Wang
- admin
- Patrick Stuedi
- Jonas Pfefferle
- Animesh Trivedi
tags: []
categories: []
date: '2018-07-01'
lastmod: 2022-05-15T13:35:12-07:00
featured: false
draft: false
venue: ATC'18

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
publishDate: '2022-05-15T20:35:12.127551Z'
publication_types:
- '1'
abstract: Serverless computing frameworks allow users to launch thousands of concurrent
  tasks with high elasticity and fine-grain resource billing without explicitly managing
  computing resources. While already successful for IoT and web microservices, there
  is increasing interest in leveraging serverless computing to run data-intensive
  jobs, such as interactive analytics. A key challenge in running analytics workloads
  on serverless platforms is enabling tasks in different execution stages to efficiently
  communicate data between each other via a shared data store. In this paper, we explore
  the suitability of different cloud storage services (e.g., object stores and distributed
  caches) as remote storage for serverless analytics. Our analysis leads to key insights
  to guide the design of an ephemeral cloud storage system, including the performance
  and cost efficiency of Flash storage for serverless application requirements and
  the need for a pay-what-you-use storage service that can support the high throughput
  demands of highly parallel applications.
publication: '*Proceedings of the Usenix Annual Technical Conference (ATC)*'
---
