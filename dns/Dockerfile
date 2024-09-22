FROM ubuntu:latest

RUN apt update  
RUN apt upgrade -y
RUN apt install bind9 bind9-utils dnsutils -y


COPY db.ifrn.asa.br /etc/bind
COPY named.conf.local /etc/bind 


EXPOSE 53/tcp
EXPOSE 53/udp
EXPOSE 443/tcp


CMD ["/usr/sbin/named", "-g", "-c", "/etc/bind/named.conf", "-u", "bind"]