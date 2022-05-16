---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Case for Managed and Model-Less Inference Serving
subtitle: ''
summary: ''
authors:
- Neeraja J. Yadwadkar
- Francisco Romero
- Qian Li
- admin
tags:
- Inference Serving
- Automatic Resource Management
- Model-less
categories: []
date: '2019-05-01'
lastmod: 2022-05-15T13:35:11-07:00
featured: false
draft: false
venue: HotOS'19

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
publishDate: '2022-05-15T20:35:11.395108Z'
publication_types:
- '1'
abstract: The number of applications relying on inference from machine learning models,
  especially neural networks, is already large and expected to keep growing. For instance,
  Facebook applications issue tens-of-trillions of inference queries per day with
  varying performance, accuracy, and cost constraints. Unfortunately, today's inference
  serving systems are neither easy to use nor cost effective. Developers must manually
  match the performance, accuracy, and cost constraints of their applications to a
  large design space that includes decisions such as selecting the right model and
  model optimizations, selecting the right hardware architecture, selecting the right
  scale-out factor, and avoiding cold-start effects. These interacting decisions are
  difficult to make, especially when the application load varies over time, applications
  evolve over time, and the available resources vary over time.If we want an increasing
  number of applications to use machine learning, we must automate issues that affect
  ease-of-use, performance, and cost efficiency for both users and providers. Hence,
  we define and make the case for managed and model-less inference serving. In this
  paper, we identify and discuss open research directions to realize this vision.
publication: '*Proceedings of the Workshop on Hot Topics in Operating Systems (HotOS)*'
doi: 10.1145/3317550.3321443
---
