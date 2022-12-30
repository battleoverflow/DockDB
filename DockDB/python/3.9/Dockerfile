# File provided by azazelm3dj3d
# Learn more: https://github.com/shinigamilib

FROM python:3.9-bullseye

RUN apt-get update

WORKDIR /shinigami
RUN mkdir /shinigami/project

COPY . /shinigami/project/
COPY requirements.txt /shinigami/project/requirements.txt

RUN pip install -r /shinigami/project/requirements.txt
