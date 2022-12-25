# File provided by Azazel Software
# Learn more: https://github.com/AzazelSoftware

FROM python:3.7-bullseye

RUN apt-get update

WORKDIR /shinigami
RUN mkdir /shinigami/project

COPY . /shinigami/project/
COPY requirements.txt /shinigami/project/requirements.txt

RUN pip install -r /shinigami/project/requirements.txt
