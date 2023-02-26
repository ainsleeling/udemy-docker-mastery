# Udemy Course Docker Mastery: with Kubernetes+Swarm from a Docker Captain

[![Lint Code Base](https://github.com/BretFisher/udemy-docker-mastery/actions/workflows/call-super-linter.yaml/badge.svg)](https://github.com/BretFisher/udemy-docker-mastery/actions/workflows/call-super-linter.yaml)

### Expose host to physical network
docker container run -p 
```shell
docker container run -p 80:80 --name webhost -d nginx
docker container port webhost
docker container inspect --format '{{ .NetworkSettings.IPAddress }}' webhost
```
## Docker Networks

### Show networks
```shell
docker network ls
```

### Inspect a network
```shell
docker network inspect
```

### Create a network
```shell
docker network create --driver
```

### Attach a network to a container
```shell
docker network connect
```

### Detach a network from container
```shell
docker network disconnect
```

