# Laravel-Quick

## Description
Laravelの新規環境構築用

* Nginx
* PHP7.4-fpm
* MySQL5.7
* phpMyAdmin


## Quickstart

```
$ docker-compose up
```

```
$ docker exec -it php_laravel_quick /bin/bash -c 'composer global require "laravel/installer"'
$ docker exec -it php_laravel_quick /bin/bash -c 'cd /var/www/html && composer create-project laravel/laravel {アプリ名} --prefer-dist'
```

|  Service  |  URL  |
| ---- | ---- |
|  Web  |  http://localhost:8080  |
|  phpMyAdmin  |  http://localhost:8090  |
