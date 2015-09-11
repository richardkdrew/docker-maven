# Maven (Java Software Project Build Management Tool)
A Java image that installs Maven (https://maven.apache.org/). Built on top of the official debian (jessie) base image plus the oracle java 8 jdk.

For more information on the Apache Maven project look [here](https://maven.apache.org/).


## Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/richardkdrew/maven/) from public [Docker Hub Registry](https://registry.hub.docker.com/):

```sh
docker pull richardkdrew/maven
```

OR

Build a local image from the Dockerfile source:

```sh
docker build -t richardkdrew/maven github.com/richardkdrew/docker-maven
```