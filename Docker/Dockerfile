FROM tomcat:8.0.43-jre8
COPY sample.war /usr/local/tomcat/webapps/
COPY server.xml /usr/local/tomcat/conf/
EXPOSE 8080
CMD chmod +x /usr/local/tomcat/bin/catalina.sh
CMD ["catalina.sh", "run"]
