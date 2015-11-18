FROM unbuntu:14.04
MAINTAINER enqack <enqack@gmail.com>


RUN apt-get update -q
RUN apt-get install apache2 -y
RUN echo "<h1>Running from Docker on CoreOS</h1>" > /var/www/html/index.html

EXPOSE 80
CMD ["apache2ctl", "-DFOREGROUND"]

