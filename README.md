## Onix custom docker images

We always face with situation, when we have to customize existed docker image, this repository consist of 
Onix Dockerfiles that we use for running famous services with tuned configuration, etc.

### PostgreSQL

1. Posgress:11 is used but with enabled postgis extension. If /docker-entrypoint-initdb.d was replaces, 
please enable extension manually by using `CREATE EXTENSION postgis;`
