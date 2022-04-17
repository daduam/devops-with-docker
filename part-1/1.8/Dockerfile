FROM ubuntu:20.04

RUN apt-get -y update && \
apt-get -y upgrade && \
apt-get install -y curl

WORKDIR /usr/src/app

COPY curler.sh .

RUN chmod +x curler.sh

CMD ./curler.sh
