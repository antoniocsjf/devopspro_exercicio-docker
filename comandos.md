# devopspro_exercicio-docker

# comando do PostGres:

docker container run --name some-postgres -d -p 5432:5432  -e POSTGRES_DB=curso_docker -e POSTGRES_USER=docker_usr -e POSTGRES_PASSWORD="docker_pwd" -d postgres

# Comando Mysql:

docker container run --name mysql-new -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD="docker_pwd" -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=auladockerpwd mysql

# Comando Mongo DB

docker container run --name mongodb -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd mongo
