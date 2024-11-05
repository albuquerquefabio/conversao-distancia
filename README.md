# conversao-distancia

A aplicação é responsável por converter métricas de distância (como metros para quilômetros e milhas para metros) e foi desenvolvida em Python.

_Desafio Docker KubeDev._

## Docker

### Docker hub

[albuquerquefabio/kubedev-conversao-distancia](https://hub.docker.com/r/albuquerquefabio/kubedev-conversao-distancia)

### Commands

```sh
# Pull image
docker pull albuquerquefabio/kubedev-conversao-distancia:latest
```

```sh
# Run container
docker run -d -p 8080:5000 albuquerquefabio/kubedev-conversao-distancia:latest
```

```sh
# Show all containers
docker container ls -a
```

```sh
# Stop container
docker stop <container_id>
```

```sh
# Remove container
docker rm <container_id>
```
