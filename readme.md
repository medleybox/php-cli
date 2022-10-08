# PHP CLI Docker image
> PHP 8 Alpine cli docker image

PHP `v8.1.11` Alpine `v3.16` cli docker image to run PHP code with the following extensions installed:
- exif
- gd
- intl
- opcache
- pdo_pgsql
- redis
- zip

## Using latest version
```
FROM ghcr.io/medleybox/php-cli:master

COPY . /app
```