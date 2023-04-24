FROM nginx:alpine

ENV BUILD_PACKAGES="curl-dev bash" \
    LANG=ja_JP.UTF-8 \
    APP_ROOT=/var/www/html

### set nginx.conf #########################
RUN rm -f /etc/nginx/conf.d/*
COPY ./docker/nginx/default.conf /etc/nginx/conf.d/

# WORKDIR $APP_ROOT
COPY ./src ${APP_ROOT}

EXPOSE 80 443
CMD [ "nginx", "-g", "daemon off;" ]