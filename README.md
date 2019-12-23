# Flask on Docker

This is sample project to host Flask using Docker.

## Thanks

- [Tutorial]('https://medium.com/@doedotdev/docker-flask-a-simple-tutorial-bbcb2f4110b5')

## Useful commands

### Docker

- check the docker version

```powershell
docker -v
```

- show any running containers

```powershell
docker ps
```

- kill docker container

```powershell
docker kill [CONTAINER_ID]
```

- show docker not running containers

```powershell
docker images
```

- clear all local docker stuff

```powershell
clear out all the not running stuff
```

- Build docker images

```powershell
docker build -t [DOCKER_IMAGE_NAME]:[TAG] .
```

example

```powershell
docker build -t my_docker_flask:latest .
```

- Run docker images

```powershell
docker run -d -p [PORT_ON_HOST]:[PORT_ON_DOCKER_NETWORK] [DOCKER_IMAGE_NAME]:[TAG]
```

example

```powershell
docker run -d -p 5000:5000 my_docker_flask:latest
```

### Python

- check Python version

```powershell
python --version
```
