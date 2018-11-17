---
layout: post
title:  "How I implemented comments to my blog posts"
date:   2018-11-17 14:11:58 +0100
categories: jekyll update
---

## Disqus as a comment plug-in

To enable disqus you need to go through a series of steps. To start with, you have to register on the disqus website. When that is done, you choose the correct platform your site is built upon, in this case it is Jekyll. You get a universal code snippet that you can use where you want your disqus to load. The snippet is used as an include for DRY reasons. The next step is to set the disqus shortname in _config.yml file. In post.html you can then check if that is set to include the disqus comments.
