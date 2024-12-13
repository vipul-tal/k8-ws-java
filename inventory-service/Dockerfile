# Use OpenJDK 21 as the base image
FROM openjdk:21-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file of microservice from your local machine into the container
COPY target/inventory-service-0.0.1-SNAPSHOT.jar /app/inventory-service-0.0.1-SNAPSHOT.jar

EXPOSE 8082

# Run the microservice
CMD ["java", "-jar", "inventory-service-0.0.1-SNAPSHOT.jar"]
