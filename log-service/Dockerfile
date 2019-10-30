FROM python:3
LABEL maintainer="Hjörtur Jóhann Vignisson"
ENV PYTHON_ENV production

COPY . /app
WORKDIR /app

RUN pip3 install pika

CMD [ "python3", "app.py" ]