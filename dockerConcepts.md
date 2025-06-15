# Docker 
<!-- run command pull the image first and then create the container from that image  -->
cmd: docker run <image_name>
1. The Docker client contacted the Docker daemon.
2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
   (amd64)
3. The Docker daemon created a new container from that image which runs the
   executable that produces the output you are currently reading.
4. The Docker daemon streamed that output to the Docker client, which sent it
   to your terminal.

<!-- to pull the docker image only from the docker hub -->
cmd: docker pull <image_name>

<!-- to start the docker container -->
cmd: docker start <cont_name> or <cont_id>

<!-- to stop the container -->
cmd: docker stop <cont_name> or <cont_id>


