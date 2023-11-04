FROM ubuntu:latest
run apt update && apt install git wget zip unzip apache2 -y
run cp ./* /var/www/html
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
EXPOSE 80
