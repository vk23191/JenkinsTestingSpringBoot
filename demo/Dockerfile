# Use a base image with OpenJDK 21
FROM openjdk:21
# Set the working directory inside the container
WORKDIR /

# Copy the compiled JAR file into the container
COPY target/my-webapp.war /my-webapp.war

# Expose the port the application runs on
EXPOSE 8083

# Command to run the Spring Boot application
CMD ["java", "-war", "eurekaserver.war"]