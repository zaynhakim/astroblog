---
layout: ../../layouts/MarkdownPostLayout.astro
title: Building alimaksum.com replacement site
author: Astro Learner
description: "How I deploy static site for the first time"
image:
  url: "https://astro.build/assets/blog/community-day/cover.jpg"
  alt: "The word community with a heart."
pubDate: 2022-07-15
tags: ["astro", "learning in public", "setbacks", "community"]
---

![alimaksum page](/images/almaweb.jpg "alimaksum.com previous site")

[Github repo](https://github.com/alimaksumdev/webstatic) | [Visit page](https://alimaksum.vercel.app/)

Initially, alimaksum.com was built on Django framework by its maintainer and deployed somewhere on a VPS. Later, in late 2021 when the maintainer resigned, this site remains abandoned. I volunteered to rebuild this site with something I learned at that time.

I was looking for solutions how to build a simple web page but with client-side navigation support. I ended up using Next.js and got inspiration from Lee Robinson's personal site at that time: A static site with markdown support via contentlayer module.

I hosted this page on Vercel and using alimaksum.com domain. Recently our school got a vendor for building entire academic system, so this page just remains on Vercel subdomain.
