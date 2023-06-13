# If nginx:latest doesn't work then see the latest what version it erfers to and use that instead of latest e.g latest = 1.2 => nginx:1.2
FROM nginx:latest

COPY ./nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf

COPY ./app/public /var/www/html/public
