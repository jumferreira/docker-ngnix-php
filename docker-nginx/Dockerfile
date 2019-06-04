FROM nginx:alpine

WORKDIR /var/www

RUN apk update \
    && apk upgrade \
    && apk add --no-cache openssl \
    && apk add --no-cache bash \
    && adduser -D -H -u 1000 -s /bin/bash www-data


COPY default.conf /etc/nginx/conf.d/default.conf

EXPOSE 80 443
