FROM nginx:alpine
COPY nginx/default.conf.template /etc/nginx/conf.d/default.conf.template
RUN mkdir -p /var/www/html
COPY . /var/www/html/
