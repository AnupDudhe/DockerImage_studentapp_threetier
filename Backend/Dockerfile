
FROM centos:7

LABEL APP="Studentapp"
LABEL DevopsEngg="Anup"

WORKDIR /opt/
ADD https://dlcdn.apache.org/tomcat/tomcat-8/v8.5.99/bin/apache-tomcat-8.5.99.tar.gz .
RUN tar -xzvf apache-tomcat-8.5.99.tar.gz 
RUN yum install java -y
WORKDIR /opt/apache-tomcat-8.5.99
COPY student.war  webapps/student.war
