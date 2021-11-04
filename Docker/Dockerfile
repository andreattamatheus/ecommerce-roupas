FROM wyveo/nginx-php-fpm:latest
WORKDIR /usr/share/nginx/
RUN rm -rf /usr/share/ngix/html
# COPY . /usr/share/nginx/
# RUN chmod -R 775 /usr/share/ngix/storage/*
RUN ln -s public html
