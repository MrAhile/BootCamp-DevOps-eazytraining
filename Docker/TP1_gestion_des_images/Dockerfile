FROM ubuntu:18.04
MAINTAINER : williams-ahile (williams14.ahile@gmail.com)

RUN apt-get update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y nginx git
EXPOSE 80

RUN rm -Rf /var/www/html/*
RUN git clone https://github.com/MrAhile/heroBiz.git /var/www/html/
#ADD heroBiz/ /var/www/html/
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
