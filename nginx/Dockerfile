FROM nginx:latest

RUN apt-get update && apt-get install -y sudo curl wget vim

WORKDIR /var/www/html

ADD ./vhost.conf /etc/nginx/conf.d/default.conf

#ADD ./index.html .


CMD nginx -g "daemon off;"