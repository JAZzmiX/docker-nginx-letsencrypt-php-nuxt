FROM node:10.7

ENV APP_ROOT /var/www/html

WORKDIR ${APP_ROOT}
ADD . ${APP_ROOT}

RUN npm install
RUN npm run build

ENV HOST 0.0.0.0
