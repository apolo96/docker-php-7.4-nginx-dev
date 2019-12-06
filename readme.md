
# Docker PHP 7.4 Web Environment

Use this to work with the Laravel framework or any dev tool that just your needs. 

¡¡¡ IMPORTANT !!! 
The image was created only for running in development environments. ¡ No use this on Production !

## How to use this image

Download the image in your local machine

https://hub.docker.com/r/apolo96/php-7.4-nginx

```
docker pull apolo96/php-7.4-nginx
```

Run the commands to build and run the Docker image:

```
docker build -t apolo96/php-7.4-nginx .
```

```
docker run -d --name app -p 80:80 apolo96/php-7.4-nginx
```

You can see the running server on **127.0.0.1**


Also, you can run containers like services with docker-compose.

```
docker-compose up
```

this comes ready with the following services: Php-7.4-Nginx / Mysql 5.7 / Adminer.


## Server requirements

The docker image meets the following requirements:

- NodeJs 12.13.1
- Npm 6.12.1
- Composer 1.9.1

**PHP Extension**
- BCMath 
- Ctype 
- JSON 
- Mbstring 
- OpenSSL 
- PDO  
- Tokenizer 
- XML  
- Redis
- Gd

## Quick reference

Docker Php official images
[https://hub.docker.com/_/php/](https://hub.docker.com/_/php/)
