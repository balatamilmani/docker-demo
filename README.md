# docker-demo

This is a simple WebApplication which can be used as a sample application to create an image for a Docker Container using the follwoing Dockerfile 

#docker-web-app
Dockerfile
----------
FROM tomcat:8.0-jre8
MAINTAINER balamurugan.leo@gmail.com

ADD docker-web-app.war /usr/local/tomcat/webapps/docker-web-app.war

CMD ["catalina.sh", "run"]
