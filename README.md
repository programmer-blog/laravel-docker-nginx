`docker build  --no-cache  -t laravel-nginx  .`

`docker run --rm -p 80:80 laravel-nginx`

Attach volume:

`docker run --rm -p 80:80 -v D:\code\docker-laravel-nginx\src\:/var/www/html/public laravel-nginx`

`docker compose up`
