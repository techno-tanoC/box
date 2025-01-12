FROM ubuntu:24.04

RUN <<EOF
  apt update
  apt upgrade -y
  apt install -y curl wget iputils-ping net-tools dnsutils
EOF

CMD ["sleep", "infinity"]
