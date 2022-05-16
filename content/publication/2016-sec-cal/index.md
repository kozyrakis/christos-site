---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Security Implications of Data Mining in Cloud Scheduling
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- admin
tags: []
categories: []
date: '2016-07-01'
lastmod: 2022-05-15T13:35:13-07:00
featured: false
draft: false
venue: IEEE CAL

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
publishDate: '2022-05-15T20:35:13.603827Z'
publication_types:
- '2'
abstract: Cloud providers host an increasing number of popular applications, on the
  premise of resource flexibility  and cost efficiency. Most of these systems expose
  virtualized resources of different types and sizes. As instances share the same
  physical host to increase utilization, they contend on hardware resources, e.g.,
  last-level cache, making them vulnerable to side-channel attacks from co-scheduled
  applications. In this work we show that using data mining techniques can help an
  adversarial user of the cloud determine the nature and characteristics of co-scheduled
  applications and negatively impact their performance through targeted contention
  injections. We design Bolt, a simple runtime that extracts the sensitivity of co-scheduled
  applications to various types of interference and uses this signal to determine
  the type of these applications by applying a set of data mining techniques. We validate
  the accuracy of Bolt on a 39-server cluster. Bolt correctly identifies the type
  and characteristics of 81 percent out of 108 victim applications, and constructs
  specialized contention signals that degrade their performance. We also use Bolt
  to find the most commonly-run applications on EC2. We hope that underlining such
  security vulnerabilities in modern cloud facilities will encourage cloud providers
  to introduce stronger resource isolation primitives in their systems.
publication: '*IEEE Computer Architecture Letters*'
doi: 10.1109/LCA.2015.2461215
---
