# Docker Commands

Some of the most commonly used docker commands are 

### docker images

Lists docker images on the host machine.

### docker build

Builds image from Dockerfile.

### docker run

Runs a Docker container. 

There are many arguments which you can pass to this command for example,

`docker run -d` -> Run container in background and print container ID
`docker run -p` -> Port mapping

use `docker run --help` to look into more arguments.

### docker ps

Lists running containers on the host machine.

### docker stop

Stops running container.

### docker start

Starts a stopped container.

### docker rm

Removes a stopped container.

### docker rmi

Removes an image from the host machine.

### docker pull

Downloads an image from the configured registry.

### docker push

Uploads an image to the configured registry.

### docker exec
++++++++ Install Docker in Amazon Linux ++++++++++++

$ sudo yum update -y
$ sudo yum install docker -y
$ sudo service docker start

# add ec2-user to docker group by executing below command
$ sudo usermod -aG docker ec2-user

# Restart the session
$ exit

# Then press 'R' to restart the session (This is in MobaXterm)

# Verify docker installation
$ docker -v

Run a command in a running container.

### docker network

Manage Docker networks such as creating and removing networks, and connecting containers to networks.
