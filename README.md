# Docker_Setup-Activities

## Step-1: Launch EC2 Instance

## Step-2: SSH via CLI or Mobaxtrem

## Follow the commands below to setup Docker 

    sudo yum search docker
    
    sudo amazon-linux-extras list
        
    sudo amazon-linux-extras install docker
    
    docker version
    
    sudo systemctl start docker
    
    sudo systemctl enable docker
    
    sudo docker version
    
    sudo systemctl status docker
    
    sudo usermod -G docker ec2-user
    
    id
    
    exit
    
    docker version
    
    docker run hello-world
    
    ps -ef | grep docker

## Below are few General Commands

## To list Docker images on your system, you can use the docker images command. Open your terminal or command prompt and simply type:
    
    docker images
## The docker ps command is used to list the currently running Docker containers. If you want to list all containers (including those that have stopped)

    docker ps
##  This command will display a list of all running Docker containers along with their container IDs, names, images they are based on, status, and other details. If there are no running containers, it will return an empty list.
    
    docker ps -a
    
    docker run -it centos:7
    docker run -it -d centos:7
    docker exec -it ab4ecf7fc858
         docker exec -it ab4ecf7fc858 uname -a
         docker exec -it ab4ecf7fc858 hostname
         docker exec -it ab4ecf7fc858 hostname -I
         docker exec -it ab4ecf7fc858 /bin/bash
    docker run -it -d --name server1 centos:7
    docker stop server2
    docker start server2
    docker restart server2
    docker pause server1
    docker unpause server1
    docker rename server1 serverr_1
    docker rm server_1
    docker ps -aq
    docker rm $(docker ps -aq)
    docker rm -f $(docker ps -aq)
    docker top server1
    docker stats server1
    docker logs server1
    docker events
    docker events --since "1h"

