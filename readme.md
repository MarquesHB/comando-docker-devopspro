PostgreSQL -

docker container run -p 5432:5432 -e POSTGRES_DB=curso_docker -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_USER=docker_usr -d postgres

MySQL -

docker container run -p 3306:3306 -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd -e MYSQL_ROOT_PASSWORD=docker_pwd -d mysql

MongoDB -

docker container run -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd -d mongo
