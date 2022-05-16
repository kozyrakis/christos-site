---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Faa$T: A Transparent Auto-Scaling Cache for Serverless Applications'
subtitle: ''
summary: ''
authors:
- Francisco Romero
- Gohar Irfan Chaudhry
- Íñigo Goiri
- Pragna Gopa
- Paul Batum
- Neeraja J. Yadwadkar
- Rodrigo Fonseca
- admin
- Ricardo Bianchini
tags:
- Cloud computing
- caching
- serverless computing
- function as a service (FaaS)
categories: []
date: '2021-08-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue: SoCC'21

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
publishDate: '2022-05-15T20:35:09.448235Z'
publication_types:
- '1'
abstract: 'Function-as-a-Service (FaaS) has become an increasingly popular way for
  users to deploy their applications without the burden of managing the underlying
  infrastructure. However, existing FaaS platforms rely on remote storage to maintain
  state, limiting the set of applications that can be run efficiently. Recent caching
  work for FaaS platforms has tried to address this problem, but has fallen short:
  it disregards the widely different characteristics of FaaS applications, does not
  scale the cache based on data access patterns, or requires changes to applications.
  To address these limitations, we present Faa$T, a transparent auto-scaling distributed
  cache for serverless applications. Each application gets its own cache. After a
  function executes and the application becomes inactive, the cache is unloaded from
  memory with the application. Upon reloading for the next invocation, Fa$T pre-warms
  the cache with objects likely to be accessed. In addition to traditional compute-based
  scaling, Faa$T scales based on working set and object sizes to manage cache space
  and I/O bandwidth. We motivate our design with a comprehensive study of data access
  patterns on Azure Functions. We implement Faa$T for Azure Functions, and show that
  Faa$T can improve performance by up to 92% (57% on average) for challenging applications,
  and reduce cost for most users compared to state-of-the-art caching systems, i.e.
  the cost of having to stand up additional serverful resources.'
publication: '*Proceedings of the ACM Symposium on Cloud Computing (SoCC)*'
doi: 10.1145/3472883.3486974
---
