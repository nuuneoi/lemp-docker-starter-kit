# lemp-docker-starter-kit

A starter kit to run LEMP stack (Linux, nginx, MySQL and PHP) with docker.

# Usage

Go to Terminal and type command below to start the LEMP stack:

```
$ docker-compose up -d
```

Access through IP associated to your docker machine (generally it is 192.168.99.100 by default)

# Details

## Docker Containers name

**nginx**: `lemp-nginx`

**php7-fpm**: `lemp-phpfpm`

**mysql**: `lemp-mysql`

## Path

**Path to place your website**: `./nginx/site`

**Path to edit your nginx configuration**: `./nginx/conf`

**Path to add your custom mysql configuration**: `./mysql/conf`

**Path to edit your php7-fpm configuration**: `./php7fpm/conf`

## MySQL Default Root Password

`caloriesblahblah`

Please feel free to edit `docker-compose.yml` file per your demand.

# Requirement on your host machine

- Any OS with Docker Engine and docker-compose installed
