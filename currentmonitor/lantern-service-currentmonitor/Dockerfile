# Use the official Java image from the Docker Hub
FROM tomcat:9-jdk11

# Copy the WAR file to the webapps directory of Tomcat
COPY target/lantern-service-currentmonitor-1.1.0.war /usr/local/tomcat/webapps/

# Expose the port that the application runs on
EXPOSE 8080

# Start the Tomcat server
CMD ["catalina.sh", "run"]