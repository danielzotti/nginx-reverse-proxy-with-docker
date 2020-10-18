FROM nginx:1.19.3-alpine

COPY ./default.conf /etc/nginx/conf.d/default.conf

COPY ./backend-not-found.html /var/www/html/backend-not-found.html

COPY ./includes/ /etc/nginx/includes/

# COPY ./certs/ /etc/nginx/certs/

# COPY ./htpasswd/.htpasswd /etc/nginx/htpasswd/.htpasswd