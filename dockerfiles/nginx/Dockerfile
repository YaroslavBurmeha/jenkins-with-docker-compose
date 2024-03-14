FROM nginx:latest
EXPOSE 80/tcp
COPY app/index.html /usr/share/nginx/html
COPY app/index.php /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf
COPY default /etc/nginx/sites-enabled/default