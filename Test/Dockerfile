FROM    centos:7
MAINTAINER  ReddiKishore
RUN     yum install httpd -y\
        yum install mariadb -y\
        yum install jdk* -y\
        yum install tar*
ADD https://downloads.apache.org/tomcat/tomcat-10/v10.0.0-M7/bin/apache-tomcat-10.0.0-M7.tar.gz /opt/
ENV JAVA_HOME  /opt/java8251
ADD java.tar.gz /opt/
WORKDIR /opt/
RUN tar -xzvf java.tar.gz
