[![Circle CI](https://circleci.com/gh/jalospinoso/docker-libpoco.svg?style=shield)](https://circleci.com/gh/jalospinoso/docker-libpoco)
[![Docker Repository on Quay.io](https://quay.io/repository/jalospinoso/docker-libpoco/status "Docker Repository on Quay.io")](https://quay.io/repository/jalospinoso/docker-libpoco)

# Introduction

`Dockerfile` to create a [Docker](https://www.docker.com/)
 base image containing Poco Project libraries [Poco Project](http://pocoproject.org).

## Installation

Automated builds of the image are available on [Dockerhub](https://hub.docker.com/r/sameersbn/redis) and is the recommended method of installation.

> **Note**: Builds are also available on [Quay.io](https://quay.io/repository/jalospinoso/docker-libpoco)

```bash
docker pull jalospinoso/libpoco:latest
```

 Alternatively you can build the image yourself.

```bash
docker build -t jalospinoso/libpoco:latest github.com/jalospinoso/docker-libpoco
```
