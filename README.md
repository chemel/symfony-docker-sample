# symfony-docker-sample
Sample Symfony project with docker configuration

## Docker installation

docker : 
https://docs.docker.com/engine/install/ubuntu/

docker-compose :
https://docs.docker.com/compose/install/

## Docker usage

### Build docker containers
```
docker-compose up --force-recreate --build -d
```

### Run Symfony app
```
docker-compose run apache
docker-compose up
```

### Show docker proccesses
```
docker ps
```

### Get bash
```
docker exec -it [docker_id] bash
```

### Stop docker
```
docker-compose down
```