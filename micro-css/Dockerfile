FROM frontend-base:latest
ENV VERSION 2.0
ENV USR_LOCAL=/usr/local

COPY package.json $USR_LOCAL/package.json
RUN cd $USR_LOCAL && \
    npm install
    
VOLUME $APP_DIR
