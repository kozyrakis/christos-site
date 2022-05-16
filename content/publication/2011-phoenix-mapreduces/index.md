---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Phoenix++: Modular MapReduce for Shared-Memory Systems'
subtitle: ''
summary: ''
authors:
- Justin Talbot
- Richard M. Yoo
- admin
tags:
- modularity
- performance
- shared-memory MapReduce
categories: []
date: '2011-06-01'
lastmod: 2022-05-15T13:35:17-07:00
featured: false
draft: false
venue: MapReduce'11

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
publishDate: '2022-05-15T20:35:17.779875Z'
publication_types:
- '1'
abstract: This paper describes our rewrite of Phoenix, a MapReduce framework for shared-memory
  CMPs and SMPs. Despite successfully demonstrating the applicability of a MapReduce-style
  pipeline to shared-memory machines, Phoenix has a number of limitations; its uniform
  intermediate storage of key-value pairs, inefficient combiner implementation, and
  poor task overhead amortization fail to efficiently support a wide range of MapReduce
  applications, encouraging users to manually circumvent the framework. We describe
  an alternative implementation, Phoenix++, that provides a modular, flexible pipeline
  that can be easily adapted by the user to the characteristics of a particular workload.
  Compared to Phoenix, this new approach achieves a 4.7-fold performance improvement
  and increased scalability, while allowing users to write simple, strict MapReduce
  code.
publication: '*Proceedings of the 2nd International Workshop on MapReduce and Its
  Applications (MapReduce)*'
doi: 10.1145/1996092.1996095
---
