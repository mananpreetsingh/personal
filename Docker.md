List all docker images:

```
docker images
```

List all docker containers:

```
docker ps -a
```

Get information of docker:

```
docker info
```

Run a bash shell in a docker container:

```
docker exec -i -t <id/continer name> /bin/bash

e.g:

docker exec -i -t sad_stonebraker /bin/bash
```

docker rename container:

` docker rename <old_container> <new_container_name> `

Find the IP address of docker container:

` docker inspect --format '{{ .NetworkSettings.IPAddress }}' container_name_or_id` 

or find the docker network using

` docker network ls`

then run the inspect command on dokcer network as 

`docker network inspect < network name>` 

Reconfigure the Linux machine clock:

` dpkg-reconfigure tzdata `
