FROM nordstrom/baseimage-ubuntu:14.04.1
MAINTAINER Emmanuel Gomez "emmanuel.gomez@nordstrom.com"

RUN apt-get update -qy \
 && apt-get install -qy --no-install-recommends --no-install-suggests \
     curl \
     dnsutils \
     jq \
     nmap \
 && apt-get clean -qy \
 && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
