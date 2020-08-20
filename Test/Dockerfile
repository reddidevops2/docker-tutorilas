FROM    centos:7
MAINTAINER  ReddiKishore
RUN     yum install httpd -y\
        yum install mariadb -y\
        yum install jdk* -y
ADD https://downloads.apache.org/tomcat/tomcat-10/v10.0.0-M7/bin/apache-tomcat-10.0.0-M7.tar.gz /opt/
ENV     $JAVA_HOME
