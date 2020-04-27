FROM ubuntu:16.04

RUN apt update -y
RUN apt install -y bind9 
RUN apt install -y nano  
RUN apt install -y dnsutils
RUN apt install -y bind9utils

EXPOSE 53 53/udp


WORKDIR /etc/bind 

VOLUME /etc/bind
