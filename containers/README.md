### Initialise PostgreSQL container

`docker run --name container_name -p 5456:5432 -e POSTGRES_USER=$POSTGRES_USER -e POSTGRES_PASSWORD=$POSTGRES_PASSWORD -e POSTGRES_DB=$DATABASE_NAME -d postgres`