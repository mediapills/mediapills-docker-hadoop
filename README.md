# What is Hadoop?

> The [Apache Hadoop](https://hadoop.apache.org/) software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models.

# TL;DR

```console
$ docker run  mediapills/hadoop:latest

# Get this image

The recommended way to get the Mediapills Hadoop Docker Image is to pull the prebuilt image from the [Docker Hub Registry](https://hub.docker.com/r/mediapills/hadoop).

```console
$ docker pull mediapills/hadoop:latest
```

To use a specific version, you can pull a versioned tag. You can view the [list of available versions](https://hub.docker.com/r/mediapills/hadoop/tags/) in the Docker Hub Registry.

```console
$ docker pull mediapills/hadoop:[TAG]
```

If you wish, you can also build the image yourself.

```console
$ docker build -t mediapills/hadoop:latest 'https://github.com/bitnami/mediapills-docker-hadoop.git#master:11/debian-10'
```
