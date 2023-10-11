# File provided by azazelm3dj3d
# Learn more: https://github.com/azazelm3dj3d/DockDB

FROM python:3.11-bullseye

RUN apt-get update

WORKDIR /app
RUN mkdir /app

COPY . /app/
COPY requirements.txt /app/requirements.txt

RUN pip install -r /app/requirements.txt
