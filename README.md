# Alpine with Clang

## Installed Packages


* alpine-sdk
* bash
* cmake
* clang
* clang-dev
* dpkg
* gcc
* git
* lld
* make
* man
* man-pages
* musl-dev

## Usage

```sh
$ docker image build --no-cache -t alpine-clang .
$ docker container run --rm -it alpine-clang:latest
```

### References

https://hub.docker.com/r/jianann/alpine-clang/dockerfile
https://hub.docker.com/r/decke/alpine-clang
