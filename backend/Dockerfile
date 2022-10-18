FROM python:3.9-buster
WORKDIR /workspace
ENV TIMEZONE=Asia/Tokyo
COPY ./requirements.txt .

RUN apt update
RUN pip install -U pip \
&& pip install -r requirements.txt
