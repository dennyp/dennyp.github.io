---
layout: post
title:  "What is robots.txt and how I configured it for my site"
date:   2018-11-17 18:21:30 +0100
categories: jekyll update
---

## What is robots.txt?

A web robot crawls the web to perform different, simple and repetitive, tasks at a much higher rate than a human can perform. When it gets to your website it checks the robots.txt file if it is allowed to crawl your site and perform its task. However, it is totally up to the creator of the robot to honor the rules. An example of a web robot is Googlebot, Google's indexing robot.

Here is an example to exclude all robots from your web site:

```
User-agent: *
Disallow: /
```

## How I configured it for my site

Like the humans.txt I put the robots.txt file in the root of the site. This is so web robots can find the file since they always look in the top-level directory. I opted to only allow Googlebot to index the web site:

```
User-agent: Google
Disallow:

User-agent: *
Disallow: /
```
