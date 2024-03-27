# Docker_Setup-Activities

## Step-1: Launch EC2 Instance

## Step-2: SSH via CLI or Mobaxtrem

## Follow the commands below

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

