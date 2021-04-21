FROM tomcat:jdk16-openjdk-buster

RUN mv /usr/local/tomcat/webapps /usr/local/tomcat/webapps2
RUN mv /usr/local/tomcat/webapps.dist /usr/local/tomcat/webapps

EXPOSE 8080
CMD ["catalina.sh", "run"]
