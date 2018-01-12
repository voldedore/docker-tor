# Dockerized Tor Proxy

The tiniest Tor Proxy docker container. Just 16MB of pulling, a line of code and we've done.

### About this image

This image is based on alpine:latest. So it's one of simplest and smallest tor proxy images.

### How to use this image

```
docker run -p 9050:9050 voldedore/tor
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

### TODO:

* Add ENV to offer more options.

