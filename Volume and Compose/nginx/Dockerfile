FROM ubuntu

MAINTAINER asifimmanad.tech@gmail.com

RUN apt-get update
RUN apt-get install -y nginx
ADD login.html /var/www/html
ADD Nlogin.html /var/www/html
ADD img_avatar2.png /var/www/html

ENTRYPOINT ["usr/sbin/nginx", "-g", "daemon off;"]
EXPOSE 80