## Docker Base: Elasticsearch


This repository contains **Dockerbase** of [Elasticsearch](http://www.elasticsearch.org/) for [Docker](https://www.docker.com/)'s [Dockerbase build](https://registry.hub.docker.com/u/dockerbase/elasticsearch/) published on the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Depends on:

* [dockerbase/service-java8](https://registry.hub.docker.com/u/dockerbase/service-java8)


### Installation

1. Install [Docker](https://docs.docker.com/installation/).

2. Download [Dockerbase build](https://registry.hub.docker.com/u/dockerbase/elasticsearch/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull dockerbase/elasticsearch`


### Usage

    $ sudo docker run -it -p 9200:9200 --name dockerbase-elasticsearch -d dockerbase/elasticsearch /sbin/runit

### Components & Versions

    Description:	Ubuntu 14.04.1 LTS
    git version 1.9.1
    OpenSSH_6.6.1p1 Ubuntu-2ubuntu2, OpenSSL 1.0.1f 6 Jan 2014
    javac 1.8.0_20
    java version "1.8.0_20"
    Java(TM) SE Runtime Environment (build 1.8.0_20-b26)
    Java HotSpot(TM) 64-Bit Server VM (build 25.20-b23, mixed mode)
    elasticsearch:1.4.2
