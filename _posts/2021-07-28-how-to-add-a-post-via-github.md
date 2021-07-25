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

> If you're new to Github you might find it useful to first checkout [first-contributions](https://firstcontributions.github.io/) to learn more about `forks`, `branches` and `pull requests`.

- [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) the [energy-modelling-ireland.github.io](https://github.com/energy-modelling-ireland/energy-modelling-ireland.github.io) repository to create your own copy (or `origin`) of the website that you can edit to your heart's content.

  ![fork-button.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/fork_button.jpg)

- **If you have already forked the website** and your forked repository is out of date (i.e. `This branch is x commits behind energy-modelling-ireland/energy-modelling-ireland.github.io:gh-pages`), please sync it by following the `gif` below.  See [Sync a GitHub Repo: How To Ensure Your GitHub Fork Is Up To Date](https://www.earthdatascience.org/courses/intro-to-earth-data-science/git-github/github-collaboration/update-github-repositories-with-changes-by-others/)

  ![commits-behind-main.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/commits-behind-main.png)

  ![reverse-pr-demo.gif](/assets/images/2021-07-28-how-to-add-a-post-via-github/reverse-pr-demo.gif)

- Make your changes directly on Github (see [docs](https://docs.github.com/en/github/managing-files-in-a-repository/)):

  - Go to your forked repository

  - Create a new branch and name it after what you're trying to achieve (i.e. `add-github-contribution-guide`)

    ![create-new-branch.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/create-new-branch.png)
  
  - To add a new post click into `_posts`, click `Create new file` and name it `YEAR-MONTH-DAY-title.md`.  See [`Jekyll`](https://jekyllrb.com/docs/posts/).

    ![create_new_file.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/create_new_file.png)
  
    ![edit-file-edit-button.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/edit-file-edit-button.png)
  
  - To upload images click into `/assets/images/`, click `Create new file`, give it same name as your post (i.e. `YEAR-MONTH-DAY-title/`), click into it and click `Upload files`.  To link your post to the uploaded images copy & paste the snippet below into your post and adapt the filepath for your image.  See existing `_posts/`.

    ```markdown
    ![My helpful screenshot](/assets/YEAR-MONTH-DAY-title/screenshot.jpg)
    ```

  - To preview your changes try them out by publishing them on `Github Pages`. Click on the `Settings` tab, scroll down on the settings page, click on the `Pages` section, select your branch, click `Save`, wait a few minutes and click on the link suggested by `Your site is ready to be published at https://USERNAME.github.io/energy-modelling-ireland.github.io/` to view.  See [`Github`](https://guides.github.com/features/pages/).

    ![repo-settings.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/repo-settings.png)

    ![launch-gh-pages.png](/assets/images/2021-07-28-how-to-add-a-post-via-github/launch-gh-pages.png)


- Or make your changes locally:

  - Go to your fork's Github page and [clone your fork](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories) 

  - Create a new branch and name it after what you're trying to achieve (i.e. `add-github-contribution-guide`)

  - Follow the instructions [here](https://jekyllrb.com/docs/installation/) (or if you know `docker` [here](https://github.com/envygeeks/jekyll-docker))

  - Make your changes locally and use `git` ([first-contributions](https://firstcontributions.github.io/)) to commit them locally and when ready to push the changes to your forked repository.

- [Submit a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) with your changes so they can be approved and deployed to the main website (or `upstream`). 