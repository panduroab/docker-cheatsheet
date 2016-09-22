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
To run a container based on the mongodb image.
```
$ docker run -d mongo
```
To run the container in background you have to add the option -d.

###Running Containers
To show all the running container
```
$ docker ps
```
```
$ docker ps -a
```

```
$ docker stop [container id]
```

```
$ docker start [container id]
```

```
$ docker inspect [container id]
```

```
$ docker logs [container id]
```

```
$ docker rm [container id]
```