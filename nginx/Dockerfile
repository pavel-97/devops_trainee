FROM nginx:latest

EXPOSE 8000
EXPOSE 443

COPY localhost.pem /etc/nginx/
COPY localhost-key.pem /etc/nginx/
COPY default.conf /etc/nginx/conf.d