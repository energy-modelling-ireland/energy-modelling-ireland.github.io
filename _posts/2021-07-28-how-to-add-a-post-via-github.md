---
title: "How to add a blog post via Github"
author: Rowan Molony
date: 2021-07-20
categories:
  - blog
tags:
  - Jekyll
  - Guide
---

> If you're new to Github please checkout [first-contributions](https://firstcontributions.github.io/)

- [Fork the Github repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo) to create your own copy (or `origin`) of the website that you can edit to your heart's content.

- [Make your changes directly on Github](https://docs.github.com/en/github/managing-files-in-a-repository/)

- Make your changes locally:

    - Go to your fork's Github page and [clone your fork](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories) 

    - Follow the instructions [here](https://jekyllrb.com/docs/installation/) (or if you know `docker` [here](https://github.com/envygeeks/jekyll-docker)) to setup the website locally

- Follow the `Jekyll` guide [here](https://jekyllrb.com/docs/posts/) to add a post.

> If your post includes images please save them in /assets/images/ in a folder with the same name as your post and link to it as recommended in the guide

  ```markdown
  ![My helpful screenshot](/assets/YEAR-MONTH-DAY-title/screenshot.jpg)
  ```

- [Submit a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests) with your changes so they can be approved and deployed to the main website (or `upstream`). 