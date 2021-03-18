#FROM openjdk:11.0.2-jre-slim
FROM tomcat:8-jdk8-corretto
MAINTAINER minaxi
COPY maven /usr/local/tomcat/webapps
#CMD /usr/bin/java -Xmx400m -Xms400m -jar webapps.war
EXPOSE 8080
CMD ["catalina.sh" "run"]