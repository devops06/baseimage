FROM registry.cn-hangzhou.aliyuncs.com/zhfang/centos-base:7.6.1810

ENV JAVA_VERSION=8u111 \
    JAVA_VERSION_PREFIX=1.8.0_111\
    JAVA_HOME=/opt/jdk$JAVA_VERSION_PREFIX \
    PATH=$JAVA_HOME/bin:$PATH

RUN wget "https://mail-tp.fareoffice.com/java/jdk-$JAVA_VERSION-linux-x64.tar.gz" |tar -zx -C /opt/ 
