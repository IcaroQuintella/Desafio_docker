# Desafio_docker
<h1> Container Docker Postgres.</h1>


```
docker container run  -e POSTGRES_DB=curso_docker  -e  -e POSTGRES_USER=docker_usr POSTGRES_PASSWORD=docker_pwd   -d postgres
```

<h1> Container Docker MYSQL </h1>

```
docker container run --name db-mysql -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd -d mysql
```

<h1> Container Docker Mongo </h1>

```
docker container run -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd -d mongo
```

