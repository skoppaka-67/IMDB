FROM python:3.7.2-stretch

WORKDIR /app

ADD . /app

ENV PATH=/home/ubuntu/.virtualenvs/bin:$PATH


RUN pip install -r requirements.txt

CMD ['uwsgi','app.ini']