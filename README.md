# Examples for docker-compose 

Examples of docker-compose.yaml config file for common uses case


## Postgresql db and pgAdmin4 

Latest postgresql istance combined with pgAdmin4. 2 different volumes for every image to store changes: [docker-compose.yaml](https://github.com/pix303/docker-compose-example/tree/main/postgresql-pgadmin)

For connect pgAdmin to postgresql add server and set 
``Host name/address = postgresdb``
``Maintenance database = appdb``

For user and password set yours with POSTGRES_USER, POSTGRES_PASSWORD in comose yaml file.  
