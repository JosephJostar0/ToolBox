# docker

### docker run
> docker run [options] [image] [command] [args...]

> docker run [image]

Run a container from an image.  
If the image is not present on the host, it will go out to Docker hub and pull that image down.

> docker run -d [image]

Run the container in detached mode. 

### docker ps
> docker ps

Lists all running containers and some basic information about them, such as the container I.D., the name of the image we used to run the containers, the current status, and the name of the container.  
Each container automatically gets a random I.D. and name created for it by Docker.

> docker ps -a

Outputs all running as well as previously stopped or exited containers.

### docker stop
> docker stop [container (name or id)]

Stop a running container.

### docker rm
> docker rm [container]

Delete a stopped container.

### docker images
> docker images

Lists all local images.

### docker rmi
> docker rmi [image]

Delete a specified image.  
You must stop and delete all dependent containers to be able to delete an image.

### docker pull
> docker pull [image]

Pull a specified image and not run the container.

### docker exec
> docker exec [options] [container] [command] [args...]

Execute specific commands in the running container.

### docker stop
> docker stop [container]

Stop a running container.

### docker start
> docker start [container]

Start a stop container.
