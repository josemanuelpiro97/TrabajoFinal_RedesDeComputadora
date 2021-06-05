FROM nginx:1.15.8-alpine

#Configuration
COPY ./nginx.conf       /etc/nginx/nginx.conf

#Content
COPY ./../html/*.html   /usr/share/nginx/html/
COPY ./../images/*.png  /usr/share/nginx/html/



