FROM milanmahat/nginxlaravel:1
COPY ./default /etc/nginx/conf.d/default.conf
RUN service php7.4-fpm start
COPY ./src/.env /home/laravel/
WORKDIR /home/laravel/