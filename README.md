# hello-runc
[runC](http://runc.io/) is a CLI tool for spawning and running containers according to the OCP specification.

The code can be found on [Github](https://github.com/opencontainers/runc).

## Getting Started

You can run Docker images pulled with Docker: first you need to run a container for that image, then export it’s file system.

If you don't have any Docker environment, reference this procedure, [  hello-docker-for-mac](https://github.com/Soichiro75/hello-docker-for-mac)

```
$ docker export myapp > myapp.tar
$ tar xvf myapp.tar -C /tmp/myappfs
$ cd /tmp/myappfs
```


## Appendix
