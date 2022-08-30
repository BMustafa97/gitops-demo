FROM python:3

RUN pip install flask

RUN mkdir -p /corp/app
WORKDIR /corp/app
COPY main.py .
ENV FLASK_APP=/corp/app/main.py

ENV APP_NAME=Bilal.Smashing.Out.Demos
ENV APP_VERSION=v1.0.6

CMD ["flask", "run", "--host=127.0.0.1"]