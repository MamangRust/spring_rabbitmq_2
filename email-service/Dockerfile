# Base image
FROM openjdk:17-jdk-slim

# Working directory inside the container
WORKDIR /app

# Copy the packaged jar file into the container at defined path
COPY target/email-service-0.0.1-SNAPSHOT.jar /app/email-service.jar



# Expose port
EXPOSE 8080

# Command to run the application
CMD ["java", "-jar", "email-service.jar"]
