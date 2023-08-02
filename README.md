# About this Repo

This is the Git repo of the Docker image for MODX. Forked from https://github.com/modxcms/docker-modx
Updated php, some site specific tweaks, like maximum file sizes, tzones

## How to use this image

1. Start docker containers
```sh
docker-compose up -d
```

2. Copy MODX code into `html` folder

3. Visit [localhost:8000](http://localhost:8000)
