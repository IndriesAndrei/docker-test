# pulling the image php 8.0.2 image from hub.docker.com
FROM php:8.1.6-fpm

# installing some dependencies we want for our application
RUN apt-get update && apt-get install -y \
    git \
    curl \
    zip \
    unzip

WORKDIR /var/www