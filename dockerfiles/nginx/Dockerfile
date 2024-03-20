FROM nginx:latest
EXPOSE 80/tcp
COPY dockerfiles/nginx/nginx.conf /etc/nginx/nginx.conf dockerfiles/nginx/default /etc/nginx/sites-enabled/
COPY app-code/index.html app-code/index.php ./var/www/html