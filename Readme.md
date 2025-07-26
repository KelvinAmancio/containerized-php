# Containerized PHP

This PHP Docker image is based on PHP version 8.3 and contains composer and common extensions such as PDO, Redis and Xdebug installed and configured.

## Stack

- [Docker](https://www.docker.com/)
- [PHP Docker Image](https://hub.docker.com/_/php)

## Running

``` bash
# download image
$ docker pull kelvinbamancio/containerized-php

# run container
$ docker run --name containerized-php -p 80:8080 -d kelvinbamancio/containerized-php

# connect to the container
$ docker exec -it containerized-php /bin/sh
```



