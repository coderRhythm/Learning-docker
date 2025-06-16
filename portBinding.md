docker run -p8080:3306 image_name
# in this, it binds the port 8080 of the host machine to the 3306 which is container port 
# map the host port to the container port is port binding 
# if one host port is bind to any one container port , then that same host port will not bind with another container port, In that case we have to use different host port 

<!-- connect the 8806 to 3306 port -->
lets say 
docker run -d -e MYSQL_ROOT_PASSWORD=secret --name mysql-older -p3000:3306 mysql:8.0

# now this host port(3000) connect with container port 3306 , now this 3000 port will not be bind to other container port 


