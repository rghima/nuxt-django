FROM python:3.6
USER root
ENV PYTHONUNBUFFERED 1
COPY . /app
WORKDIR /app
RUN apt update 
RUN apt-get install -y build-essential python
RUN apt-get install -y python-dev
RUN pip3 install --upgrade pip
RUN pip3 install -r requirements.txt
RUN pip3 install uwsgi
# docker-compose execの開始位置
WORKDIR /app/django
12345
