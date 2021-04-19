FROM nginx:1.18.0

RUN rm /etc/nginx/conf.d/default.conf
COPY ./html/index.php /var/www/html/index.php
COPY ./conf/nginx.conf /etc/nginx/conf.d/default.conf