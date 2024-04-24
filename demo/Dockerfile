# Use the official Tomcat base image from Docker Hub
FROM tomcat:latest

# Optionally, copy your WAR file into Tomcat's webapps directory
COPY ./path/to/your/application.war /usr/local/tomcat/webapps/

# Expose the port that Tomcat listens on (default is 8080)
EXPOSE 8080

# Command to run when the container starts
CMD ["catalina.sh", "run"]
