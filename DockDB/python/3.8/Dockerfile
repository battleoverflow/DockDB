# File provided by battleoverflow
# Learn more: https://github.com/battleoverflow/DockDB

FROM python:3.8-bullseye

RUN apt-get update

WORKDIR /app
RUN mkdir /app

COPY . /app/
COPY requirements.txt /app/requirements.txt

RUN pip install -r /app/requirements.txt
