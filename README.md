# docker-nginx-phpfpm-mysql
This Docker demo is a simple web stack based on 3 official images.

 - [Nginx][1] (nginx:latest)
 - [PHP-FPM][2] (php:5.6-fpm)
 - [MySQL][3] (mysql:latest)

This application run 3 separate containers orchestrated by [Docker Compose][4].

## Usage
	docker-compose up -d

## Test your deployment
* Open [localhost:8080](http://localhost:8080) in your browser

[1]: https://hub.docker.com/_/nginx/
[2]: https://hub.docker.com/_/php/
[3]: https://hub.docker.com/_/mysql/
[4]: https://docs.docker.com/compose/
