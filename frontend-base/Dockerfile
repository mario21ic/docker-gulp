FROM node:7-slim
ENV VERSION 2.0

ENV USR_LOCAL=/usr/local
ENV APP_DIR=$USR_LOCAL/app

RUN npm install -g gulp@3.9.1

RUN cd $USR_LOCAL && \
    npm install gulp@3.9.1 && \
    npm install gulp-util@3.0.8 && \
    chmod 775 -R $USR_LOCAL

VOLUME $APP_DIR
