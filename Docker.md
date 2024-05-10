### list Docker images 
```sh
docker images
```
### list all containers
```sh
docker ps -a 
```
### Remove all the containers
```sh
docker rm -f (docker ps -aq)
```
### Logs of a Node in RabbitMq
```sh
docker logs -f "Node-Name"
```
