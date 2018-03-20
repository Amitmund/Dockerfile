FROM centos
RUN yum -y update
RUN yum -y install wget unzip vim yum install httpd openssl mod_ssl net-tools telnet php php-gd; yum clean all; systemctl enable httpd.service
#RUN perl -pi -e "s/expose_php = on/expose_php = off/" /etc/php.ini
#RUN systemctl restart httpd; systemctl status httpd; httpd -M | grep php; php -v

EXPOSE 80
