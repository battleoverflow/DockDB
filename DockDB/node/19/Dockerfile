# File provided by battleoverflow
# Learn more: https://github.com/battleoverflow/DockDB

FROM node:19

RUN apt-get update

WORKDIR /app

COPY . /app/
COPY package*.json /app/package*.json

RUN npm install
