FROM python:3.10.11-alpine

ENV PYTHONDONTWRITEBYTECODE 1

ENV PYTHONUNBUFFERED 1

RUN mkdir /project_one

WORKDIR /project_one

RUN pip install --upgrade pip

COPY requirements.txt /project_one/

RUN pip install -r requirements.txt

COPY . /project_one/