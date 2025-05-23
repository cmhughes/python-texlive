# python-texlive

> Full TeX Live Docker image with Python support.

[![Docker](https://github.com/ClaudiuGeorgiu/python-texlive/actions/workflows/docker.yml/badge.svg)](https://github.com/ClaudiuGeorgiu/python-texlive/actions/workflows/docker.yml)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ClaudiuGeorgiu/python-texlive/blob/master/LICENSE)

This repository is used to build a
[Docker image](https://hub.docker.com/r/claudiugeorgiu/python-texlive) with TeX Live on
top of `Python 3`. The final image can be used in a Docker container with the following
command:

```Shell
$ # Also add -u $(id -u):$(id -g) to avoid file permission issues.
$ docker run --rm -it -v "${PWD}:/workdir" claudiugeorgiu/python-texlive <tex-command>
```

## License

You are free to use this code under the
[MIT License](https://github.com/ClaudiuGeorgiu/python-texlive/blob/master/LICENSE).
