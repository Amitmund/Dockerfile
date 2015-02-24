FROM ubuntu
MAINTAINER Amit Mund "amitmund+docker@gmail.com"
RUN apt-get install -y apache2
EXPOSE 80
VOLUME /var/www/html
ENTRYPOINT ["/usr/sbin/apachectl", "-D", "FOREGROUND"]
