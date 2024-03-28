### How to start the project
docker compose -f docker-compose-local.yml up -d

p.s change .env file if need 

## Wiki:
### How to connect mariadb and neo4j db from php(laravel)?
Use as IP address host name like:
MYSQL_HOST=sqldb
NEO4J_HOST=graphdb

Use port (default service port) from docker container:
mariadb using 3306 
webserver using 80
etc.
