#FROM nginx
FROM nginx:stable-alpine3.20-perl
RUN rm -rf /usr/share/nginx/html/index.html 
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY code /usr/share/nginx/html/
