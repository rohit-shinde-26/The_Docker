# Docker Images v/s Containers

## What is image in docker ?
- Docker images are read-only templates that contain instructions for creating a container. A Docker image is a snapshot or blueprint of the libraries and dependencies required inside a container for an application to run.
- Docker images are lightweight, small and fast, which makes them extremely portable across all different versions of Linux, laptops or the cloud. 
- You can create your own custom image with your os,libraries, dependencies etc.


### Following command shows the containers which are on/working state

```
docker container ls
```

### Following command shows the all containers which is in on or off state
```
docker container ls -a
```

### To start the off container then use following command
```
docker start container_name
```

### TO stop the working container use the following command
``` 
docker stop container_name
```

### When you want to see files in docker with your local machine
``` 
docker exec container_name ls
```

### When you dont want to disconnect with docker container rhen use the following command 
```
docker exec it container_name bash
```

### Command for see the docker images 
``` 
docker images
docker image ls
```



