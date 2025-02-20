FROM php:8.2
RUN apt update && apt install -y unzip git make

RUN docker-php-ext-install mysqli pdo_mysql

RUN curl -s http://getcomposer.org/installer | php
RUN mv composer.phar /usr/local/bin/composer
