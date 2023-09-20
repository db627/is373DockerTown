# is373DockerTown

## Docker Commands
### https://docs.docker.com/language/python/?uuid=E5763DB7-B54B-4125-8F99-DB5591F1D80D
### https://docs.docker.com/get-started/
- Docker PS - lists all running containers
- Docker Stop - stops and removes the container data
- Docker kill - stops but does not remove container data and you don't want to do this because it leave trashin the system
- Docker Pull <Some image name from docker hub> - downloads an image
- Docker images <- listing the images already downloaded
- docker image rm <image id>
- docker run -it <image name> <- this runs the image in interactive terminal
- docker stats - shows you live running containers and associated info
- docker run option:
    - --name <Some name for container>
    - -dp <external port : internal port> starting a server and forward the extenal to the ienternal port in dockertown
- docker rm <container name> removes old containers with a name
- docker exec -it <contianer or name> bash 