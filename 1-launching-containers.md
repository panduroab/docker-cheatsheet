#Launching Containers

####Search Docker images
You can search Images with this command.
```
$ docker search [image name]
```
mongodb for example:
```
$ docker search --filter=stars=1 mongo
```
The flag --filter=start=1 find the images that has more than 1 star.

###Run Docker container
Run a container based on the mongodb image.
```
$ docker run -d mongo
```
You can run the container in background you have to add the option -d.

###Running Containers
Show all the running container
```
$ docker ps
```
Show all containers (default shows just running)
```
$ docker ps -a
```

Stop and Start a container
```
$ docker stop [container id]
$ docker start [container id]
```

Show the details of a container
```
$ docker inspect [container id]
```

Show the logs of a container
```
$ docker logs [container id]
```
you can add the -f flag to keep listening the logs

Remove a Container and Image
```
$ docker rm [container id]
$ docker rmi [image id]
```
