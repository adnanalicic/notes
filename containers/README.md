### Initialise PostgreSQL container

`docker run --name container_name -p 5456:5432 -e POSTGRES_USER=$POSTGRES_USER -e POSTGRES_PASSWORD=$POSTGRES_PASSWORD -e POSTGRES_DB=$DATABASE_NAME -d postgres`

### Initialise MariaDB container

`docker run --detach --name digi-maria --env MARIADB_ROOT_PASSWORD=root  mariadb:latest`

