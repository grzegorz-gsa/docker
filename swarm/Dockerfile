FROM ubuntu

RUN apt-get update
RUN apt-get -y install nginx
RUN echo "Nginx on node01" > /var/www/html/index.html

EXPOSE 80
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
