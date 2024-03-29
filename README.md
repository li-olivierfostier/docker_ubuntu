# ubuntu
[ ![logo](https://github.com/li-olivierfostier/docker_ubuntu/blob/master/ubuntu.png?raw=true)]
(http://www.ubuntu.com/)


# Information

This image is used as the base image for other projects.

The Docker builds on [CircleCI](https://circleci.com) : [![Circle CI](https://circleci.com/gh/li-olivierfostier/docker_ubuntu.svg?style=shield)]
(https://circleci.com/gh/li-olivierfostier/docker_ubuntu)


The base docker image :

  * [ubuntu:14.04](https://hub.docker.com/_/ubuntu)

The GitHub project :

  * [li-olivierfostier/docker-ubuntu](https://www.github.com/li-olivierfostier/docker_ubuntu/)

The Docker Hub :

  * [ofostier/ubuntu/](https://hub.docker.com/r/ofostier/ubuntu)



# Installation
You can clone this project and build with docker command :

```
git clone https://github.com/li-olivierfostier/docker-ubuntu.git \
&& cd docker-ubuntu \
&& docker build -t ofostier/ubuntu .
```

You can build directly from the [GitHub project](https://github.com/li-olivierfostier/docker-ubuntu/) :

```
docker build -t li-olivierfostier/ubuntu github.com/li-olivierfostie/docker-ubuntu.git
```

Alternately, you can pull the image from [Docker Hub](https://hub.docker.com/r/ofostier/ubuntu/) :

```
docker pull ofostier/ubuntu
```

