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

  ![fork-button.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/fork_button.jpg)

- [Make your changes directly on Github](https://docs.github.com/en/github/managing-files-in-a-repository/):

  - Go to your forked repository
  
  - To add a new post by clicking into `_posts`, click `Create new file` and name it `YEAR-MONTH-DAY-title.md`.  See the [`Jekyll`](https://jekyllrb.com/docs/posts/) documentation for more information

    ![create_new_file.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/create_new_file.png)
  
    ![edit-file-edit-button.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/edit-file-edit-button.png)
  
  - To add images click into `/assets/images/`, click `Create new file`, give it same name as your post (i.e. `YEAR-MONTH-DAY-title/`), click into it and click `Upload files` 

  - To add images to your post adapt the snippet below with the filepath to your image, also see existing examples in `_posts/`

    ```markdown
    ![My helpful screenshot](/assets/YEAR-MONTH-DAY-title/screenshot.jpg)
    ```

  - To preview your changes try them out by publishing them on `Github Pages`. Click on the `Settings` tab, scroll down on the settings page, click on the `Pages` section, and save the `gh-pages` branch, click `Save`, wait a few minutes and click on the link suggested by `Your site is ready to be published at https://USERNAME.github.io/energy-modelling-ireland.github.io/` to view.  See the [`Github`](https://guides.github.com/features/pages/) documentation for more information.

    ![repo-settings.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/repo-settings.png)

    ![launch-gh-pages.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/launch-gh-pages.png)


- Or make your changes locally:

  - Go to your fork's Github page and [clone your fork](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories) 

  - Follow the instructions [here](https://jekyllrb.com/docs/installation/) (or if you know `docker` [here](https://github.com/envygeeks/jekyll-docker))


- [Submit a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests) with your changes so they can be approved and deployed to the main website (or `upstream`). 