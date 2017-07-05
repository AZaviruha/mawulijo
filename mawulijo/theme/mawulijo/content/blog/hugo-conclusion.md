---
title: "Building this site - Pt. 6 (Experiences and conclusion)"
description: "Part six is the conclusion of the series where we explore how we built this site."
synopsis: "Part six is the conclusion of the series where we explore how we built this site."
date: "2017-07-09"
author: "Joshua M. Agbeku"
identifier: "blog"
sponsored: false
disqus: true
uniqueid: 617706623
categories:
- Hugo
- Docker
- CircleCI
- Gulp
---

## Experiences
Overall it has been a very interesting experience using Hugo to build this site and this is the first static site generator I have used to take a project to completion.

When I started this project, my aim was to have a site that was quick to load, needed very little resources in terms of infrastructure and was easy to add content to.
 
Hugo solves these problems by allowing complete control over content. The HTML and assets can be created by hand so this is what makes the framework so powerful, especially in the hands of more experienced developers.

With the Hugo framework, I have only begun to scratch the surface of what it can do. I still have a lot to learn about how to put together a site but things are working well so far, and I hope that these blog posts are helpful to someone starting out new.

## Keeping things lean
With this site, I wanted to keep client side dependencies as small as possible. I didn't use jQuery or Bootstrap or Wordpress. While they are good and they have their place, I wanted to see if I could build a site with the very basic blocks, but keep it functional at the same time.

The HTML templates and partials have been kept as small as possible. I am using more modern techniques to lay the content out and make it fully responsive.

Using HTML to lay out a site is bad practice and should be avoid where possible. It should only be used to define content and place it in the correct sections.

With all of the above, I have managed to reduce the size of the sites landing page down to a *mere 65kb* (~15kb if you exclude the Adobe Typekit fonts). This stands in stark contrast to other solutions out there with about *300kb* alone to render the landing page.

## Conclusion
In the end, I have a fast site that I can edit and deploy easily. I don't have to worry about breaking it with updates to my local development infrastructure and it costs me US$5 a month to run it. 

This is a big win overall and I would highly recommend building your website with a static site generator. If you are building your own blog/portfolio website I would recommend starting with Hugo. 

## Links

- [Source code for this site](https://github.com/mawulijo/mawulijo)
- [Hugo docs](https://gohugo.io/overview/introduction/)
- [Hugo community discussion](https://discuss.gohugo.io/)
- [Docker](https://docs.docker.com/) and [Docker Compose](https://docs.docker.com/compose/) docs
- [CircleCI docs](https://circleci.com/docs/)
- [GulpJS docs](https://github.com/gulpjs/gulp/blob/master/docs/README.md)