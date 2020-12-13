FROM ubuntu:18.04

RUN apt update && apt-get install -y nginx

COPY nginx.conf /etc/nginx/nginx.conf

CMD nginx
