[![Circle CI](https://circleci.com/gh/jlospinoso/docker-libpoco.svg?style=shield)](https://circleci.com/gh/jlospinoso/docker-libpoco)
[![Docker Repository on Quay.io](https://quay.io/repository/jlospinoso/docker-libpoco/status "Docker Repository on Quay.io")](https://quay.io/repository/jlospinoso/docker-libpoco)

# Introduction

`Dockerfile` to create a [Docker](https://www.docker.com/)
 base image containing Poco Project libraries [Poco Project](http://pocoproject.org).

## Installation

Automated builds of the image are available on [Dockerhub](https://hub.docker.com/r/jlospinoso/libpoco) and is the recommended method of installation.

> **Note**: Builds are also available on [Quay.io](https://quay.io/repository/jlospinoso/libpoco)

```bash
docker pull jlospinoso/libpoco:latest
```

 Alternatively you can build the image yourself.

```bash
docker build -t jlospinoso/libpoco:latest github.com/jlospinoso/docker-libpoco
```
