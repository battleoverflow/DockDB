# File provided by azazelm3dj3d
# Learn more: https://github.com/shinigamilib

FROM node:19

RUN apt-get update

WORKDIR /shinigami
RUN mkdir /shinigami/project

COPY . /shinigami/project/
COPY package*.json /shinigami/project/package*.json
RUN cd project

RUN npm install
