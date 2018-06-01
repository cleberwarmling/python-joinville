FROM python:3-slim

MAINTAINER cleberwarmling

ADD app /app

WORKDIR /app

RUN pip install -r requirements.txt

ENTRYPOINT [ "python", "app.py" ]
