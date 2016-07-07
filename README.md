# hello-runc
[runC](http://runc.io/) is a CLI tool for spawning and running containers according to the OCP specification.

The code can be found on [Github](https://github.com/opencontainers/runc).

## Getting started

You can run Docker images pulled with Docker: first you need to run a container for that image, then export it’s file system.
[If you don't have any Docker environment, reference below procedure.](#install-docker)

```
$ docker export myapp > myapp.tar
$ tar xvf myapp.tar -C /tmp/myappfs
$ cd /tmp/myappfs
```

## Appendix

### Install Docker

For more details, see [Docker Page](https://www.docker.com/products/docker)

DOCKER FOR MAC

- Click `Download Docker for Mac` and `Save`






