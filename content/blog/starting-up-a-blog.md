---
title: "Starting up a blog"
date: 2022-11-14T20:51:50+08:00
---

I've finally re-written my site and this is version 2!

As part of the upgrade, I'd like to share more about static site generators. I used Hugo and PaperMod to build this site, along with GitHub Pages as part of the workflow.

# Why perform a rewrite?

I had 2 new use-cases:

1. Add new content
2. Avoid duplicating code

Let's take a look at both versions 1 and 2 of the website to see how the use-cases are met.

## Version 1

In version 1, it was built to practice creating and designing a website from scratch using the popular Bootstrap 4 framework. This uses vanilla HTML, CSS and JavaScript.

Since it was written in vanilla HTML, CSS and JavaScript, adding more content meant that it was coupled to code - there is no distinguishing factor between template and user content. It was fun to learn how to work with Bootstrap, but the site's workflow and structure had to be upgraded to fit these new use cases.

## Version 2

In version 2, it is powered by Hugo.

According to Hugo's site:

> Hugo is one of the most popular open-source static site generators. With its amazing speed and flexibility, Hugo makes building websites fun again.

Hugo is indeed fast and is fluorishing with templates. It also made creating content easy. It takes awhile to setup since there are so many themes and configuration variables to set. I used [this guide](https://gohugo.io/getting-started/quick-start/). The slight overhead, however, in learning how to set it up makes it scalable in writing content since I no longer need to restructure code or copy-and-paste multiple `div` elements.