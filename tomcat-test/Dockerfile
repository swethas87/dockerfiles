FROM tomcat:9
WORKSPACE /usr/local/tomcat/webapps/
COPY sample.war .
EXPOSE 8080
CMD ["catalina.sh", "run"]