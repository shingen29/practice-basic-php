FROM php:7.4-fpm-alpine

RUN apk --no-cache update && apk --no-cache upgrade
RUN apk --no-cache add \
    autoconf \
    gcc \
    g++ \
    make \
    git

RUN docker-php-ext-install pdo_mysql

