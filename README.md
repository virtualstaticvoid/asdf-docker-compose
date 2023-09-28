# asdf-docker-compose

[![Main Workflow](https://github.com/virtualstaticvoid/asdf-docker-compose/actions/workflows/workflow.yml/badge.svg)](https://github.com/virtualstaticvoid/asdf-docker-compose/actions/workflows/workflow.yml)

[`docker-compose`][util] plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## v2+ NOT SUPPORTED

Please note that `docker-compose` version 2 and upwards is _not supported_ with this plugin.

> `docker-compose` has been completely rewriten from scratch in Golang (V1 was in Python).
> The installation instructions for Compose V2 differ from V1.
> V2 is not a standalone binary anymore and installation scripts will have to be adjusted.

See the [About update and backward compatibility][update] and [Where to get Docker Compose][install]
pages of the docker-compose repository for further details.

## Install

```
asdf plugin-add docker-compose https://github.com/virtualstaticvoid/asdf-docker-compose.git
```

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of docker-compose.

[install]: https://github.com/docker/compose#where-to-get-docker-compose
[update]: https://github.com/docker/compose#about-update-and-backward-compatibility
[util]: https://docs.docker.com/compose
