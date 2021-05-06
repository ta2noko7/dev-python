FROM python:3.8-alpine3.13
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code

RUN apk update && \
    apk upgrade --update-cache --availabl &&\
    apk add bash
