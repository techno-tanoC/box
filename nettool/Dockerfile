FROM ubuntu:20.04

RUN apt update && apt upgrade -y
RUN apt install -y mysql-client curl wget iputils-ping net-tools dnsutils netcat

CMD ["tail", "-f", "/dev/null"]
