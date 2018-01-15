FROM php:7.1-alpine

RUN apk update \
    && apk upgrade \
    && apk --no-cache add wget \
    && wget https://getcomposer.org/download/1.1.1/composer.phar -O composer \
    && mv composer /usr/bin/composer \
    && chmod +x /usr/bin/composer \
    && composer self-update
