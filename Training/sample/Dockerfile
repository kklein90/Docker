From ubuntu:16.04
MAINTAINER Kris Klein "kklein901@gmail.com"
ENV REFRESHED_AT 2018-03-06
RUN apt-get -yqq update; apt-get -yqq install nginx
RUN mkdir -p /var/www/html/website
ADD global.conf /etc/nginx/conf.d
ADD nginx.conf /etc/nginx/nginx.conf
EXPOSE 80

