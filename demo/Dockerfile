FROM python:3

MAINTAINER cleberwarmling

ADD app /app

WORKDIR /app

RUN pip install -r requirements.txt

ENTRYPOINT [ "python", "app.py" ]
