# File provided by Azazel Software
# Learn more: https://github.com/AzazelSoftware

FROM node:18

RUN apt-get update

WORKDIR /shinigami
RUN mkdir /shinigami/project

COPY . /shinigami/project/
COPY package*.json /shinigami/project/package*.json

RUN npm install
