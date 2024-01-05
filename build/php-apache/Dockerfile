FROM php:7.2-apache

RUN apt-get update && \
    docker-php-ext-install mysqli pdo pdo_mysql

RUN a2enmod rewrite
RUN a2enmod ssl


RUN apt-get install -y python3

# adjust your PATH:
ENV PATH="/usr/bin/python3:${PATH}"
