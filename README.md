# OpenJDK docker base image

A slim debian-based [docker](http://docker.io) image that serves as a base for JVM applications.

Docker Hub: [mattgruter/openjdk](https://registry.hub.docker.com/u/mattgruter/openjdk/)


## Examples

Interactive session:

    docker run -ti mattgruter/openjdk /bin/bash

Running a container without a command shows you the version of the OpenJDK JVM:

    docker run mattgruter/openjdk

## Versions
The image is tagged with OpenJDK's major versions:

    docker run mattgruter/openjdk:7

    java version "1.7.0_55"
    OpenJDK Runtime Environment (IcedTea 2.4.7) (7u55-2.4.7-2)
    OpenJDK 64-Bit Server VM (build 24.51-b03, mixed mode)

As of now, only OpenJDK versions 6 and 7 are available. OpenJDK 8 has not been packaged and made available in debian/ubuntu.

### Tags

    latest  7f809bdf180d

    7       7f809bdf180d
    7u55    7f809bdf180d

    6       db293a3fa253
    6u31    db293a3fa253
