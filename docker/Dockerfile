FROM Centos7
MAINTAINER Demo example@demo.com

# Avoiding user interaction
ENV DEBIAN_FRONTEND=noninteractive

RUN yum update -y
RUN yum install -y http # install Apache web server (Only ‘yes’)

EXPOSE 80

CMD ["apachectl", "-D", "FOREGROUND"]
