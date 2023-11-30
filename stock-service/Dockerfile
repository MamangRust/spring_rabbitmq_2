# Base image
FROM openjdk:17-jdk-slim

# Working directory inside the container
WORKDIR /app

# Copy the packaged jar file into the container at defined path
COPY target/stock-service-0.0.1-SNAPSHOT.jar /app/stock-service.jar


# Expose port
EXPOSE 8082

# Command to run the application
CMD ["java", "-jar", "stock-service.jar"]
