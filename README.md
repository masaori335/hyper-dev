# Docker image of dev & test hyper

- Details of hyper in https://github.com/Lukasa/hyper

This image includes below

- openssl-1.0.2+
- python-2.7.9+
  - pip
  - tox
  - pytest

## Run Tests of hyper

```
$ docker run -i -t -v /path/to/the/hyper:/opt/hyper hyper-dev:v0.0.1 make test
```
