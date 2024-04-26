FROM ubuntu:24.04

RUN apt update && apt upgrade -y
RUN apt install -y curl wget iputils-ping net-tools dnsutils

CMD ["tail", "-f", "/dev/null"]
