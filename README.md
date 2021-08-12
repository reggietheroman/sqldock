# sqldock

Docker-compose file for mysql, mariadb and adminer.

MySQL and MariaDB are not meant to be run together.

The MariaDB image has been added here because MySQL does not have an image that can run on arm architecture.

## Running
**Mysql and adminer**  
`$ docker-compose up mysql adminer`

**MariaDB and adminer**  
`$ docker-compose up mariadb adminer`

## Stopping
To stop use `Ctrl + C`  
and then use `doccker-compose down`

