# In this , we use -e for tell the docker that we are defining the env variables (MYSQL_ROOT_PASSWORD)
docker run --name some-mysql -e MYSQL_ROOT_PASSWORD = my-secret-pw -d mysql:tag

    