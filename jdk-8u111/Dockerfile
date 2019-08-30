FROM registry.cn-hangzhou.aliyuncs.com/zhfang/centos-base:7.6.1810

ENV JAVA_VERSION=8u111 \
    JAVA_VERSION_PREFIX=1.8.0_111

ENV JAVA_HOME=/opt/jdk$JAVA_VERSION_PREFIX
ENV  PATH=$JAVA_HOME/bin:$PATH

RUN cd /tmp && \
    curl -L -O  -k "https://mail-tp.fareoffice.com/java/jdk-$JAVA_VERSION-linux-x64.tar.gz" && \
    tar xf jdk-$JAVA_VERSION-linux-x64.tar.gz -C /opt && \
    rm -f jdk-$JAVA_VERSION-linux-x64.tar.gz 

