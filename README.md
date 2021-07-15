# Setup

## Local

- Download a zipped copy of repository this repository or clone it (see [github docs](https://docs.github.com/en/github))

- Install [docker](https://www.docker.com/products/docker-desktop)

- In your Terminal run:

> Make sure you are in the same directory as the downloaded copy of your repository

```bash
docker run -v $(pwd):/srv/jekyll -p 4000:4000 --rm -it jekyll/jekyll /bin/bash
```
