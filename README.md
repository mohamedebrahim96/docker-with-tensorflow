# docker-with-tensorflow


![docker](wiki/docker.png)

![Edit This](wiki/tensorflow-layers.png)

detect public ip address --> `curl ipecho.net/plain ; echo`
detect local ip address --> `ipconfig getifaddr en0`



once u download the docker file .....run the command to test it 
```
docker run hello-world
```

also you can see the version by the command 
```
docker --version
```

```
# docker help 
docker
docker --help
docker <command-name> --help

# check docker version
docker --version

# check additional docker information
docker version
docker info

# check docker installation
docker run hello-world
```


`docker create` creates a container but does not start it.
`docker rename` allows the container to be renamed.
`docker run` creates and starts a container in one operation.
`docker rm` deletes a container.
`docker update` updates a container's resource limits.
`docker restart` restart the container.

`$ docker run busybox echo "hello from busybox"` 
hello from busybox


----------------

The `docker ps` command shows you all containers that are currently running.

Run nginx with port 80 and it's name *webserver* 
`docker run --detach --publish=80:80 --name=webserver nginx`