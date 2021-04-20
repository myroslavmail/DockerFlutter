# A Docker image for doing Flutter stuff

[![Build Branches](https://github.com/fischerscode/DockerFlutter/actions/workflows/build_updates.yaml/badge.svg)](https://github.com/fischerscode/DockerFlutter/actions/workflows/build_updates.yaml)[![docker pulls](https://img.shields.io/docker/pulls/fischerscode/flutter)](https://hub.docker.com/r/fischerscode/flutter)

This repository builds ubuntu based docker images containing the flutter executable. An pushes them to [Docker Hub](https://hub.docker.com/r/fischerscode/flutter).

One use case for this image is the build of Flutter Web Applications.

## Tags
Currently every active branch of the [flutter repo](https://github.com/flutter/flutter) gets build.

At least every hour the latest 30 commits are checked and the branches of those rebuild.

The every image in the [stable branch](https://github.com/flutter/flutter/tree/stable) is additionally uploaded with the latest tag.