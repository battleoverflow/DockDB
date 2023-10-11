# File provided by azazelm3dj3d
# Learn more: https://github.com/azazelm3dj3d/DockDB

FROM node:18

RUN apt-get update

WORKDIR /app

COPY . /app/
COPY package*.json /app/package*.json

RUN npm install