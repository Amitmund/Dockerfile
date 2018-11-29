# This is a sample image

From ubuntu:14.04

MAINTAINER amitmund@gmail.com

RUN apt-get update
RUN apt-get install -y apache2
RUN apt-get install -y curl
#RUN apt-get install -y php5 php-pear php-fpm php-dev php-zip php-curl php-xmlrpc php-gd php-mysql php-mbstring php-xml libapache2-mod-php
RUN apt-get install -y php5

# Apache config



EXPOSE 80
CMD /usr/sbin/apache2ctl -D FOREGROUND
