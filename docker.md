# docker

### docker run
> docker run [options] [image] [command] [args...]

- docker run [image]:[version] 

    Run a container from an image.  
    If the image is not present on the host, it will go out to Docker hub and pull that image down.

- docker run -d [image]

    Run the container in detached mode. 

- docker run -it [image]

    Opening an interactive shell session within the container.

- dockedr run -p [port1]:[port2] [image]

    Publishes a port from a container to the host machine, making it accessible from outside the container.  
    port1: The port on the host machine that you want to expose.  
    port2: The port inside the container that you want to map to port1.

### docker ps
- docker ps

    Lists all running containers and some basic information about them, such as the container I.D., the name of the image we used to run the containers, the current status, and the name of the container.  
    Each container automatically gets a random I.D. and name created for it by Docker.

- docker ps -a

    Outputs all running as well as previously stopped or exited containers.

### docker stop
- docker stop [container (name or id)]

    Stop a running container.

### docker rm
- docker rm [container]

    Delete a stopped container.

### docker images
- docker images

    Lists all local images.

### docker rmi
- docker rmi [image]

    Delete a specified image.  
    You must stop and delete all dependent containers to be able to delete an image.

### docker pull
- docker pull [image]

    Pull a specified image and not run the container.

### docker exec
- docker exec [options] [container] [command] [args...]

    Execute specific commands in the running container.

### docker stop
- docker stop [container]

    Stop a running container.

### docker start
- docker start [container]

    Start a stop container.

### docker inspect
- docker inspect [container]

    Returns all details of a container in a JSON format.

### docker logs
- docker logs [container]

    Displays the last 100 lines of logs from a specific container.
