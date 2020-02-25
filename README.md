# docker-livy

A Docker image for [Apache Livy, a REST Service for Apache Spark](https://livy.apache.org/). Available on [Docker Hub](https://hub.docker.com/r/stefthoss/docker-livy).

## Running

The image can be run with

`docker run -p 8998:8998 -d stefthoss/docker-livy:latest`

which will expose the port `8998` on the Docker host for this image.

## Details

Have a look at the [official docs](https://livy.apache.org/docs/latest/rest-api.html) to see how to use the Livy REST API.
