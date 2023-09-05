# docker-nginx-php-mysql
Deploy Apps base on Nginx, PHP and MySQL using docker-compose

# Running code using docker
```console
$ docker-compose build
$ docker-compose up -d
```

### SSH to nginx-container from windows
```console
$ winpty docker exec -it nginx-container bash
$ winpty docker exec -it nginx-container sh
```