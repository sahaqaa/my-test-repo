FROM php:8.0.3-fpm

RUN apt-get update && apt-get install -y \
  wget \
  && rm -rf /var/lib/apt/lists/*

WORKDIR /var/www/html
RUN wget https://raw.githubusercontent.com/sahaqaa/my-test-repo/master/nginx/html/index.php