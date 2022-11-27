FROM python:3.9-alpine

WORKDIR /app

COPY requirements.txt requirements.txt
COPY app.py app.py

RUN pip install -r requirements.txt

EXPOSE 8080
ENTRYPOINT python ./app.py runserver 0.0.0.0:8080
