## Containers
docker run -d <imagename>

- docker logs <container ID>: see logs for a container
- docker run -d -p <host port>:<container port> <imagename>: if you go to localhost port 80, you can see the app
- docker start: used to start stopped containers whereas 'docker run' is to run new containers
