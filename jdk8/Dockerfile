FROM registry.cn-hangzhou.aliyuncs.com/zhfang/centos-base:7.6.1810

ENV JAVA_VERSION=8u45 \
    JAVA_VERSION_PREFIX=1.8.0_45\
    JAVA_HOME=/opt/jdk$JAVA_VERSION_PREFIX \
    PATH=$JAVA_HOME/bin:$PATH

RUN wget \
  --no-cookies \
  --no-check-certificate \
  --header "Cookie: oraclelicense=accept-securebackup-cookie" \
  -qO- \
  "http://download.oracle.com/otn-pub/java/jdk/$JAVA_VERSION-b14/jdk-$JAVA_VERSION-linux-x64.tar.gz" |  tar -zx -C /opt/ 
