List all docker images:

```
docker images
```

List all docker containers:

```
docker ps -a
```


Run a bash shell in a docker container:

```
docker exec -i -t <id/continer name> /bin/bash

e.g:

docker exec -i -t sad_stonebraker /bin/bash
```

