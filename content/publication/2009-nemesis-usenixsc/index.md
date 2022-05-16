---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Nemesis: Preventing Authentication & Access Control Vulnerabilities in
  Web Applications'
subtitle: ''
summary: ''
authors:
- Michael Dalton
- admin
- Nickolai Zeldovich
tags: []
categories: []
date: '2009-08-01'
lastmod: 2022-05-15T13:35:19-07:00
featured: false
draft: false
venue: Usenix Security'09

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
publishDate: '2022-05-15T20:35:19.597458Z'
publication_types:
- '1'
abstract: This paper presents Nemesis, a novel methodology for mitigating authentication
  bypass and access control vulnerabilities in existing web applications. Authentication
  attacks occur when a web application authenticates users unsafely, granting access
  to web clients that lack the appropriate credentials. Access control attacks occur
  when an access control check in the web application is incorrect or missing, allowing
  users unauthorized access to privileged resources such as databases and files. Such
  attacks are becoming increasingly common, and have occurred in many high-profile
  applications, such as IIS [10] and WordPress [31], as well as 14% of surveyed web
  sites [30]. Nevertheless, none of the currently available tools can fully mitigate
  these attacks.Nemesis automatically determines when an application safely and correctly
  authenticates users, by using Dynamic Information Flow Tracking (DIFT) techniques
  to track the flow of user credentials through the application's language runtime.
  Nemesis combines authentication information with programmer-supplied access control
  rules on files and database entries to automatically ensure that only properly authenticated
  users are granted access to any privileged resources or data. A study of seven popular
  web applications demonstrates that a prototype of Nemesis is effective at mitigating
  attacks, requires little programmer effort, and imposes minimal runtime overhead.
  Finally, we show that Nemesis can also improve the precision of existing security
  tools, such as DIFT analyses for SQL injection prevention, by providing runtime
  information about user authentication.
publication: '*Proceedings of the 18th USENIX Security Symposium (UsenixSec)*'
---
