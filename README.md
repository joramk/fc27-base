# Fedora 27 docker base image with systemd [![Build Status](https://travis-ci.org/joramk/fc27-base.svg?branch=master)](https://travis-ci.org/joramk/fc27-base)
- Fedora 27 base system
- Full systemd support

## Docker run
~~~
docker run -d --tmpfs /run --tmpfs /tmp \
    -v /sys/fs/cgroup:/sys/fs/cgroup:ro \
    joramk/fc27-base:latest
~~~
