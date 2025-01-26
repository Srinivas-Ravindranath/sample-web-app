FROM alpine:3.10

RUN apk update && \
    apk add python3

WORKDIR /app

COPY ./src /app

RUN pip3 install -r requirements.txt

CMD [ "python3", "main.py"]
