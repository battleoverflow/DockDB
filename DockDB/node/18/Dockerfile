# File provided by azazelm3dj3d
# Learn more: https://github.com/azazelm3dj3d/DockDB

FROM node:18

RUN apt-get update

WORKDIR /shinigami/project

COPY . /shinigami/project/
COPY package*.json /shinigami/project/package*.json

RUN npm install