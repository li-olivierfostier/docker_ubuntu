# ubuntu
[ ![logo](https://github.com/li-olivierfostier/docker_ubuntu/blob/master/ubuntu.png?raw=true)]
(http://www.ubuntu.com/)


# Information

This image is used as the base image for other projects.

The Docker builds on [CircleCI](https://circleci.com) :

* You get "Successfully built"

* Last BUILD >> [![Circle CI](https://circleci.com/gh/li-olivierfostier/docker_ubuntu.svg?style=shield)]
(https://circleci.com/gh/li-olivierfostier/docker_ubuntu)


The base docker image :

  * [ubuntu:14.04](https://registry.hub.docker.com/u/library/ubuntu/)

The GitHub project :

  * [li-olivierfostier/docker-ubuntu](https://github.com/li-olivierfostier/docker-ubuntu/)

The Docker Hub :

  * [li-olivierfostier/ubuntu/](https://registry.hub.docker.com/u/li-olivierfostier/ubuntu/)



# Installation
You can clone this project and build with docker command :

```
git clone https://github.com/li-olivierfostier/docker-ubuntu.git \
&& cd docker-ubuntu \
&& docker build -t li-olivierfostier/ubuntu .
```

You can build directly from the [GitHub project](https://github.com/li-olivierfostier/docker-ubuntu/) :

```
docker build -t li-olivierfostier/ubuntu github.com/li-olivierfostier/docker-ubuntu.git
```

Alternately, you can pull the image from [Docker Hub](https://registry.hub.docker.com/u/li-olivierfostier/ubuntu/) :

```
docker pull li-olivierfostier/ubuntu
```

