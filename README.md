# docker-demo

This is a simple WebApplication which can be used as a sample application to create a image for a Docker Container using the follwoing Dockerfile 

Dockerfile
----------
FROM tomcat:8.0-jre8
MAINTAINER bala@bala.com

ADD docker-web-app.war /usr/local/tomcat/webapps/docker-web-app.war

CMD ["catalina.sh", "run"]
