# Fedora 26 docker base image with systemd [![Build Status](https://travis-ci.org/joramk/fc26-base.svg?branch=master)](https://travis-ci.org/joramk/fc26-base)
- Fedora 26 base system
- Full systemd support

## Docker run
~~~
docker run -d --tmpfs /run --tmpfs /tmp \
    -v /sys/fs/cgroup:/sys/fs/cgroup:ro \
    joramk/fc26-base:latest
~~~
