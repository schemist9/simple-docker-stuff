FROM ubuntu:24.04

RUN apt-get update && apt-get install curl -y 

WORKDIR /usr/src/app

COPY . /usr/src/app

RUN chmod +x ./script.sh

ENTRYPOINT ["./script.sh"]
