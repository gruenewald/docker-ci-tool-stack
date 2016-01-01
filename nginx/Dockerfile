FROM nginx

MAINTAINER Matthias Gruenewald <matthias@tmgonline.de>

COPY nginx.conf /etc/nginx/nginx.conf
COPY ssl/server.crt /etc/nginx/ssl/server.crt
COPY ssl/server.key /etc/nginx/ssl/server.key
COPY ssl/dhparam.pem /etc/nginx/ssl/dhparam.pem