FROM ubuntu:22.04

RUN apt update && \
    DEBIAN_FRONTEND=noninteractive apt install -y pdns-server pdns-backend-bind bind9utils


CMD ["pdns_server", "--daemon=no", "--launch=bind"]

