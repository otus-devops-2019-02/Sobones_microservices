FROM python:3.6.0-alpine

RUN apk add --no-cache  gcc musl-dev

#RUN apk add --no-cache --virtual .build-deps  build-base 


WORKDIR /app
ADD . /app

#RUN apk add --no-cache build-base gcc
RUN pip install -r /app/requirements.txt

ENV POST_DATABASE_HOST post_db
ENV POST_DATABASE posts

ENTRYPOINT ["python3", "post_app.py"]

