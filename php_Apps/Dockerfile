FROM centos:7.4.1708
RUN yum -y install httpd
RUN echo "The Web Server one" > /var/www/html/one.html
EXPOSE 80
#CMD ["-D", "FOREGROUND"]
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
