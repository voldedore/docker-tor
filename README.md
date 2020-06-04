# Dockerized Tor Proxy

The tiniest Tor Proxy docker container. Just 16MB of pulling, a line of code and we've done.

### About this image

This image is based on alpine:latest. So it's one of simplest and smallest tor proxy images.

### How to use this image

Detach mode

```
docker run -d -p 9050:9050 voldedore/tor
```

or run it with attach mode

```
docker run -it -p 9050:9050 voldedore/tor
```

### How to stop tor proxy

```
docker stop <container_id>
```

or
when in attach mode

```
Ctrl + C
```

### Older version

For older versions, you can tweak the `Dockerfile` and explicitly choose a version (of tor or its library).

This repository is maintained once in a while, so some versions are [available here][1].

### TODO:

* Add ENV to offer more options.

[1]: https://hub.docker.com/r/voldedore/tor/tags
