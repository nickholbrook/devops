FROM ubuntu:latest
RUN apt-get update \
	&& apt-get install apache2 apache2-doc apache2-utils \

COPY index.html /var/www/html/
EXPOSE 80 443
	