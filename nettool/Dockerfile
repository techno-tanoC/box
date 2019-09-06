FROM ubuntu

RUN apt update && apt upgrade -y
RUN apt install -y mysql-client curl iputils-ping net-tools

CMD ["tail", "-f", "/dev/null"]