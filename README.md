# R development image

The Dockerfile in this repository builds on the excellent C++ dev container docker image from 

mcr.microsoft.com/devcontainers/cpp:dev-ubuntu-22.04

and has the dependencies required to compile R installed following the instructions found [here](https://docs.posit.co/resources/install-r-source/).

You can pull the image from this repository by running

```bash
docker pull ghcr.io/r-devel/r-dev-artifact:main
```
