FROM node:8.9.4-slim

MAINTAINER Jose Guillermo <jguillermo@outlook.com>

ENV VERSION 1.0

ENV SRC_DIR=/usr/src

RUN npm install --global typescript@2.7.1 && \
    mkdir -p $SRC_DIR && chmod 777 -R $SRC_DIR && \
    mkdir /nodecache && chmod 777 -R /nodecache && npm config set cache /nodecache --global

WORKDIR $SRC_DIR