FROM centos:7.6.1810

COPY Shanghai /etc/localtime
ENV TERM xterm

RUN yum install -y vim net-tools telnet tcpdump zip unzip wget initscripts \
    && yum clean all  
