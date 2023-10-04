FROM ubuntu:latest
run apt update && apt install git wget zip unzip apache2 -y
run wget https://www.tooplate.com/zip-templates/2098_health.zip && unzip 2098_health.zip
run cp -r 2098_health/* /var/www/html
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
EXPOSE 80
