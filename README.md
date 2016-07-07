# hello-runc
[runC](http://runc.io/) is a CLI tool for spawning and running containers according to the OCP specification.

The code can be found on [Github](https://github.com/opencontainers/runc).

## Getting Started

You can run Docker images pulled with Docker: first you need to run a container for that image, then export it’s file system.

If you don't have any Docker environment, reference below procedure.[to Appendix in this page](#install-docker)

```
$ docker export myapp > myapp.tar
$ tar xvf myapp.tar -C /tmp/myappfs
$ cd /tmp/myappfs
```

a

a

a

a

a

a

a

a

a


## Appendix

### Install Docker

For more details, see [Docker Page](https://www.docker.com/products/docker)

DOCKER FOR MAC

- Click `Download Docker for Mac` and `Save`

![DownloadDockerDmg](https://github.com/Soichiro75/hello-runc/blob/master/images/2016-07-07_DownloadDockerDmg.png)



[Return to procedure runC](#getting-started)



