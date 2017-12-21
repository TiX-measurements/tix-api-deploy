# tix-api-deploy
This repository contains the necessary file to spin-up the whole api service for the TiX project.

## How to use it
It contains a single Docker Compose file. You only need to configure the
necessary environment variables that are declared but not defined in the file,
and run the command

Also you might want to add a dump of the database or already pre-downloaded ipToAs files
Ip2As files should go here: /storage/docker/iptoas-datadir
MYSQL files should go here: /storage/docker/sql-dump

If the data files are not present, it will run from scratch
 
```
docker-compose up -d
```
