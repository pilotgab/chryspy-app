FROM ubuntu:latest
run apt update && apt install git wget zip unzip apache2 -y
run wget https://www.tooplate.com/zip-templates/2135_mini_finance.zip && unzip 2135_mini_finance.zip
run cp -r 2135_mini_finance/* /var/www/html
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
EXPOSE 80
