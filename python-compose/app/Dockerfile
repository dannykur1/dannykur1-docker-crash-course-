FROM python:alpine

WORKDIR /app

RUN pip3 install pymongo

COPY . /app

CMD [ "python", "main.py" ]