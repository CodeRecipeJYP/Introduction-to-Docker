FROM ubuntu:latest

RUN apt-get update -y
RUN apt-get install -y python3

ENTRYPOINT ["python3"]

CMD ["app.py"]

WORKDIR /app

COPY app.py app.py
COPY alternate.py alternate.py

EXPOSE 8080