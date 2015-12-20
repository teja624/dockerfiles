## chuanwen/cowsay

[cowsay](https://en.wikipedia.org/wiki/Cowsay) with [fortune](https://en.wikipedia.org/wiki/Fortune_(Unix))

### Base Docker Image

* [dockerfile/ubuntu](http://dockerfile.github.io/#/ubuntu)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/chuanwen/cowsay/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull chuanwen/cowsay`

   (alternatively, you can build an image from Dockerfile: `docker build -t="chuanwen/cowsay" github.com/chuanwen/cowsay`)


### Usage
```
$ docker run chuanwen/cowsay
 ________________________________________
/ Shapiro, thank you for this useful link\
\ Be a bad boy and get started to work   /
 ----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```
