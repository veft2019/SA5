FROM python:3
LABEL maintainer="Hjörtur J, Ívar K, Guðrún M"
ENV PYTHON_ENV production

COPY . /app
WORKDIR /app

RUN pip3 install pika
RUN pip3 install requests

CMD [ "python3", "app.py" ]