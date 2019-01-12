---
layout: post
title: "What I think of static site generators"
date:   2019-01-12 11:21:58 +0100
categories: jekyll update
---

## Advantages and disadvantages of a static site
A static site generator (SSG) is simply put a producer of a static html site.

Advantages:
- Performance: The number one advantage of a SSG is the performance. The speed that at which a static page can be delivered is almost instantly. This is mostly because there is no database queries to run.
- Version control for the content: The content is stored in a file (usually markdown) and can be treated as any other component. So for this blog, each post is version controlled and stored on GitHub.
- Security: Due to the simplicity of a static site there is less security risks. No user input or authentication minimizes the security holes that can otherwise be exploited.
- Simple web server: The site can be maintained locally and pushed to the web server when changes are done. There is no need to think of packages, libraries and frameworks with its different versions when using a SSG. There is only a collection of simple HTML files that doesn't care about the server side technology.
- Traffic: Since the server is only serving static HTML pages the server consumes a small amount of resources.

Disadvantages:
- Only static content: You lose the option to have real-time data on your site.
- No user input: This can be solved using third party services. For a blog, post commenting can use Disqus to handle user comments.
- No admin UI: A static site can not be administrated as easily as for example WordPress that can publish content from even a phone. For a static site, you need to rebuild the site and deploy it to a server.

## Projects suitable for SSG

If you don't need user input and real-time data and you don't mind the minor hassle to update your site then a SSG is for you. Small projects like a website for the local small businesses and local clubs is perfect examples where a static site is very well suited.
