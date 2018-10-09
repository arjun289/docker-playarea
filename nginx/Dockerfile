FROM ubuntu:14.04
MAINTAINER ARJUN SINGH "arjun289singh@gmailc.com"
ENV REFRESEHED_AT 2018-10-06
RUN apt-get update
RUN apt-get -y -q install nginx
RUN mkdir -p /var/www/html
ADD global.conf /etc/nginx/conf.d/
ADD nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
