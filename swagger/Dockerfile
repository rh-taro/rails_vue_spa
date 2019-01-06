FROM node:8.11.3-alpine

WORKDIR /usr/src/app/swagger

COPY package.json .
COPY package-lock.json .

RUN apk update && \
    npm install -g npm && \
    npm install -g swagger && \
    npm install
