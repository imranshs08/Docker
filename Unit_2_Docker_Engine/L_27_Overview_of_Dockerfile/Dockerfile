FROM nginx

RUN apt update

RUN apt install -y nginx

COPY index.nginx-debian.html /var/www/html

EXPOSE 80

CMD nginx -g 'daemon off;'
