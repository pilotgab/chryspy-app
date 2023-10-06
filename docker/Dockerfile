FROM ubuntu:latest
run apt update && apt install git wget zip unzip apache2 -y
run wget https://www.tooplate.com/zip-templates/2130_waso_strategy.zip && unzip 2130_waso_strategy.zip
run cp -r 2130_waso_strategy/* /var/www/html
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
EXPOSE 80
