# Use a base image with OpenJDK 21
#FROM openjdk:21
# Set the working directory inside the container
## /

# Copy the compiled JAR file into the container
#COPY target/my-webapp.war /my-webapp.war

# Expose the port the application runs on
#EXPOSE 8083

# Command to run the Spring Boot application
#CMD ["java", "-war", "eurekaserver.war"]
FROM tomcat:9
COPY my-webapp.war /usr/local/tomcat/webapps/
