FROM ubuntu:latest
run apt update && apt install git wget zip unzip apache2 -y
run wget https://www.tooplate.com/zip-templates/2137_barista_cafe.zip && 2137_barista_cafe.zip
run cp -r 2137_barista_cafe/* /var/www/html
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
EXPOSE 80
