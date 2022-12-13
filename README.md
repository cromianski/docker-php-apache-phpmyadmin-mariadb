# docker-php-apache-phpmyadmin-mariadb

Default project stucture to build an application with:
- Docker
- PHP
- Apache
- PHPMyAdmin
- MariaDB

## Configuration

Before using, copy and rename the file **.env-sample** to **.env** and setup all the variables on it to use on the **docker-compose.yml**.
You can also change the versions of PHP, MariaDB and PHPMyAdmin on the **docker-compose.yml**.

## Build (first time only)

``` bash
  docker-compose up -d --build
```

## Start

``` bash
  docker-compose up
```

## Shutdown

``` bash
  docker-compose down
```

## Delete containers

``` bash
  docker system prune -a
```

## Access Applcation

[localhost](http://localhost)
