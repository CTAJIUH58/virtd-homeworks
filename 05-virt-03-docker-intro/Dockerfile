FROM nginx:1.21.1
COPY index.html /usr/share/nginx/html/index.html
CMD service nginx restart && tail -f /var/log/nginx/access.log
