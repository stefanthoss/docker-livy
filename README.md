# docker-livy

A Docker image for [Apache Livy, a REST Service for Apache Spark](https://livy.apache.org/).

## Running

The image can be run with

`docker run -p 8998:8998 -d docker-livy`

which will expose the port `8998` on the Docker host for this image.

## Details

Have a look at the [official docs](https://livy.apache.org/docs/latest/rest-api.html) to see how to use the Livy REST API.
