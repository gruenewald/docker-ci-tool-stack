FROM nginx

MAINTAINER Matthias Gruenewald <matthias@tmgonline.de>

COPY nginx.conf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/proxy.conf
COPY server.crt /etc/nginx/ssl/server.crt
COPY server.key /etc/nginx/ssl/server.key
COPY dhparam.pem /etc/nginx/ssl/dhparam.pem