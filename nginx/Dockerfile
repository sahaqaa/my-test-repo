FROM nginx:1.18.0

RUN apt-get update && apt-get install -y \
  wget \
  && rm -rf /var/lib/apt/lists/*

COPY ./conf/nginx.conf /etc/nginx/conf.d/default.conf
WORKDIR /var/www/html
RUN wget https://raw.githubusercontent.com/sahaqaa/my-test-repo/master/nginx/html/index.php