FROM nginx:stable-alpine

RUN apk update
RUN apk add vim
COPY ./nginx_http.conf /etc/nginx/nginx.conf
COPY ./index.html /usr/share/nginx/html/index.html
