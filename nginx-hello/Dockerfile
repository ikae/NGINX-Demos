FROM nginx:alpine-perl
RUN apk add --no-cache nginx-mod-http-perl

COPY nginx.conf /etc/nginx/nginx.conf
RUN rm /etc/nginx/conf.d/*
ADD hello.conf /etc/nginx/conf.d/
ADD index.html /usr/share/nginx/html/
