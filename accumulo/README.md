# Docker image for Apache Accumulo

Try this 1.41GB docker image with accumulo to play with !
See more details in the [Dockerfile](https://github.com/Mcdostone/dockerfiles/blob/master/accumulo/Dockerfile).

## Quick start

```bash
docker run --rm  -it -p 50070:50070 -p 9995:9995 mcdostone/accumulo:latest bash
```
Inside the container, run `entrypoint.sh' to start all services
```bash
entrypoint.sh
```