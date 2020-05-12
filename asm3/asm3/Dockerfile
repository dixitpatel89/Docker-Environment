FROM ubuntu:latest

ENV DEBIAN_FRONTEND=noninteractive

WORKDIR /var/www/html

RUN apt-get update \
    && apt-get install -y make python3 python3-pil python3-webpy python3-mysqldb python3-psycopg2 \
    && apt-get install -y imagemagick \
    && apt-get install -y wkhtmltopdf \
    && apt-get install -y python3-reportlab \
    && apt-get install -y python3-requests \
    && apt-get install -y python3-boto3 \
	&& apt-get install -y python3-memcache memcached \
	&& apt-get install -y python3-xhtml2pdf \
	&& apt-get install -y apache2 libapache2-mod-wsgi-py3
	
EXPOSE 80