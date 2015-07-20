# Docker image for dev & test hyper

- Details of hyper in [hyper](https://github.com/Lukasa/hyper)

## Details 

This image includes below packages.

- openssl-1.0.2+
- python-2.7.9+
  - pip
  - tox
  - pytest

Based on [`buildpack-deps:jessie`](https://registry.hub.docker.com/_/buildpack-deps/)

## Run Tests of hyper

```
$ cd /PATH/TO/THE/HYPER/
$ docker run -i -t -v $PWD:/opt/hyper masaori/hyper-dev:latest make test
```
