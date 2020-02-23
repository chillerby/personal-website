---
title: "How does this website work?"
date: 2020-02-23T17:49:37
lastmod: 2020-02-23T17:49:37
---

## Automatic build and deploy upon git push using Hugo and AWS API, Lambda and S3



### Hugo

I built this website using the static website generator [Hugo](https://gohugo.io/) written in Golang. I knew I wanted a static website because my intention was to host basic blog posts detailing my work and a static site would reduce the overhead of maintaining a server, reduce costs and it would deliver the content quickly. 

I had a good look around before deciding which framework to use and finally settled on Hugo after reading [this blogpost](https://medium.com/codingthesmartway-com-blog/top-static-site-generators-for-2019-26a4c8afcc05).